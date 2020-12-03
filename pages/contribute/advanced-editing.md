---
layout: page
title: Advanced Editing
permalink: advanced-editing
keywords: contribute, write, markdown, tutorial
sidebar: default_sidebar
categories: [contribute, tutorial]
toc: true
---

So you want to edit the wiki, but the [beginner's tutorial](/how-to-contribute) isn't good enough for you? Perhaps you need to change the structure of the sidebar, or maybe you're making lots of changes and want to do it on your own computer. Maybe you have some experience with git and prefer the command line interface to the web interface. Maybe you're just wondering where we got the theme and what the heck I did to it to make dynamic sidebars possible. Whatever the case, this article will explain how to edit and host a copy of the site locally, along with how the site is made and how to change the theme yourself. 

## Anatomy of THE Scrolls
This site is hosted on Github Pages from [this repository](https://github.com/thebestrobotics/thebestrobotics.github.io). Github pages uses a tool called Jekyll to compile your site and hosts it for free. Plenty of information on these tools is available online. 

The theme we are using is mostly a clone of the theme found [here](https://github.com/tomjoht/documentation-theme-jekyll), but with one important modification: dynamic sidebars. 

### Dynamic Sidebars
The file "_includes/sidebar.html" has been heavily modified to make the dynamic sidebar functionality possible. I won't explain it here, but if you're interested in learning how this is done, download a copy of the default file from the theme repository and compare it with the file on this site. 

## Local Editing
Github has a cache in front of the site that means it can take a few minutes to see your changes. For editing normal pages, this is fine, but for changing things like the sidebars that show up on every page and follow specific syntax, you'll want to see the site update quickly and preferrably before you publish changes. 

The solution is to set up Jekyll and Git locally on your computer. The process shouldn't be too difficult, especially if you already have some experience with the command line. A tutorial on how to install Jekyll can be found [here](https://jekyllrb.com/docs/installation/). 

If you're reading this article, chances are you already have a favorite interface for interacting with git. If not, [Sourcetree](https://www.sourcetreeapp.com/) might be a good option. Many solutions are available online, so find one that looks good to you. 

Once you're set this up, you should be able to clone the site's repository and then host it locally using Jekyll. You can make your edits using your favorite text editor and reload your browser to see changes in real time. This should be a lot more convenient for doing non-trivial tasks. 

## Editing the Sidebar
At some point the current sidebar will need to be edited. It's stored in the file "_data/sidebars/default_sidebar.yml". It's written in YAML, although there's really no need to learn YAML to edit it. You should be able to figure it out just by looking at the current sidebar as an example. 

Be careful with syntax, since Jekyll can be picky and YAML is a bit hard to write. When you've edited the file, Jekyll should automatically regenerate the site and you should see the new sidebar as soon as you reload your browser. Make sure to check the links!

### Dynamic Sidebar Folders
You can make a folder or subfolder dynamic rather than specifying the items that go in it directly. This is useful so that multiple users making different changes don't all need to edit the sidebar, resulting in a messy merge. To do this, add the "is_dynamic: true" and "category: category_name" property to the folder, replacing "category_name" with the name of the category that you want to show up in the folder. 