---
layout: page
title: Contribute to THE Scrolls
permalink: /contribute-to-the-scrolls/
---

THE Scrolls are supposed to retain all of the knowledge acquired by THE over the years, and is therefore constantly in need of new authors to update the site with the newest information. Here is how to contribute to THE Scrolls and become a master of ancient knowledge: 

1. Create a Github account
2. Get access to the repository
3. Create a feature branch
4. Find or create a page
5. Write some ancient wisdom
6. Merge your changes
7. View your changes live
8. Delete the feature branch

## Step 1: Create a Github account
This is the easiest step of all of them. Head over to [github.com](https://github.com) and create an account. It's free and only takes a few minutes. 

## Step 2: Get access to the repository
Now, you need to email us at [robotics@texomahomeeducators.org](mailto:robotics@texomahomeeducators.org) to get access. You should receive an email from Github prompting you to accept the invitation to contribute. It can take a few minutes from the time the invite is sent for the email from Github to arrive, so be patient. 

## Step 3: Create a feature branch
Once you've accepted the invitation to the repository, you can visit it by going to [the repository page on Github](https://github.com/thebestrobotics/thebestrobotics.github.io). Once you're there, you will need to create a feature branch to push your changes. 

Branches are basically your own copy of the website that you can work on without worrying that anyone will overwrite your changes. Once you're done writing, you'll be able to take the changes you've made in this isolated workspace and merge them back in to the primary branch (called main). You should create a new branch for every 

Once you're on the repository page, you'll want to click on the dropdown that likely says "main". Then you'll want to type the name of your new branch in the text dropdown that appears. There's no hard and fast rule on what to name it, but try to describe the change you are trying to make (for example, the branch used to write this page was named "write-contribute-page"). Once you've typed your name, click on the "create branch: your-branch-name 'from main'" button that appears. See the image below for an example: 

![Creating a feature branch](/images/contribute-create-branch.png)

As long as you are making changes that belong in this "feature", you should make sure that you are working in this branch. To do this, make sure the dropdown now says the name of your branch where it used to say "main". If it doesn't, click the dropdown and search for your branch. It should appear in the menu. Don't create a new one if you've already made one! Once you click on it you will switch to that branch and you will be ready to make changes. 

## Step 4: Find or create a page

Most changes will be made in the "pages" folder. First go to the repository page and make sure you're in the feature branch you created earlier. Then look at the list in the middle of the page. There should be an entry there called "pages" with a blue folder icon to the left of it. Click on it to move into the pages folder. 

![Navigating to the pages folder](/images/contribute-pages-folder.png)

What you need to do next depends on whether you're trying to create a new page or edit an existing one. Note that you can do both, and usually you will (for example, to create a new page and link to it from an existing one). See the appropriate header below: 

### Create a new page

Once you're in the "pages" folder, you should click on the "add file" dropdown. You can either choose "create a new file" to write your text online, or you can choose "upload files" if you've already written the content you want to post on your own computer (don't do this without first looking at step 5, below). In any case, the file needs to end with a ".markdown" extension, not ".txt" or ".html". Again, there's no real rules on how to name files, but name it something relevant to what it's about. 

![Creating a new page](/images/contribute-add-file.png)

If you choose to create a new file, you'll be taken to the online markdown editor. Type in a file name and the following header: 
```
---
layout: page
title: Name here
permalink: /link-here/
---
```
Don't forget the three dashes at the top and bottom of the header - they're very important. Replace "Name here" with a nice name for your page and "link-here" with a nice name to link to your page. Make sure these don't conflict with other pages already on the site. Once you've done that, you can proceed to step 5. 

### Edit an existing page

Editing an existing page is only slightly easier than creating a new one. Once you're in the "pages" folder, find the page you want to edit in the list of files. Click on it and you'll see a preview of what the file looks like now. Click the edit button (it looks like a pencil) in the top-right corner of the preview to go to the online markdown editor. 

![Where to find the edit button](/images/contribute-edit-button.png)

Once you've done that, you should see that you're able to edit the file contents. Proceed to step 5. 

## Step 5: Write some ancient wisdom

This is the part where you actually write whatever it is you wanted to write. The last step should have taken you to the online editor, where you can edit the contents of a page. 

Everything on this site should be written in markdown, which compiles to professional-looking HTML but is also perfectly readable as plain text. If you aren't familiar with markdown, don't worry - learning the basics should take less than 5 minutes. A simple and quick guide to using markdown on github can be found [here](https://guides.github.com/features/mastering-markdown/). 

Write your ancient wisdom in markdown. You can click the "Preview changes" tab to see roughly how your markdown will look when it's deployed to the web. Keep writing until that tab looks good and you've said all you want to say. 

When you are done, scroll to the bottom of the editor page. Type a short description of the changes you made in the textbox just under "commit changes". You can write an extended description if you feel like more than a sentence is necessary for others to understand what you did. When you're done, click the green "Commit changes" button to save your work. 

![Committing your changes](/images/contribute-commit.png)

## Step 6: Merge your changes

**Not completed**
