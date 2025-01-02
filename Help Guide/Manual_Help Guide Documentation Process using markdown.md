> To maintain confidentiality, this sample does not show Specific product links, git repository names, product screenshots, etc.

## Purpose and Scope
- To clone the Git repository of product Documentation on a local machine.
- To write product help page content using markdown language in VS code.
- To publish written content on the product website.

## Overview

### Cloning a repository 
When you create a repository on GitHub.com, it exists as a remote repository. You can clone your repository to create a local copy on your computer and sync between the two locations.
### Markdown 
Markdown is a lightweight markup language for creating formatted text using a plain-text editor. To learn the basics of Markdown, refer to [guide](https://www.markdownguide.org/).

### VS Code
VS Code supports Markdown files out of the box. You just start writing Markdown text, save the file with the .md extension, and then you can toggle the visualization of the editor between the code and the preview of the Markdown file; obviously, you can also open an existing Markdown file and start working with it. To switch between views, press Ctrl+Shift+V in the editor. You can view the preview side-by-side (Ctrl+K V) with the file you are editing and see changes reflected in real-time as you edit.

## Procedure
The process of product help page creation and publishing on the website is divided into the following stages:

### Steps of Git Repository Cloning
- Install Git and VS code on your local machine.
- Open the command prompt and enter syntax to create a product folder (eg: *"ProductDocs"*) in the D:/ drive.

### Steps of Writing Content in Markdown
- Open VS Code and go to File-> Open the *“ProductDocs”* folder.
- Open the required page and write content in the markdown.
- For new folder or page creation, go to D:\ProductDocs location and add a new folder /file.

> The file names should have an extension “.md” (folder names do not require any extension).

### Steps of Publishing the Content 
- Once you are done with the changes on the page, review and save it **(Ctrl+S)**.
- Go to Source control **(Ctrl+shift+G)** and click on the three dots.
- Select Stash-> **Stash**. Enter a message. 
- Select Stash->**Pop** Latest stash.

> Note: If multiple users are working on the same project, select Pull to pull changes from the repository before running this step.

- Stage changes by clicking on the **“+”** icon.
- The selected changes for the commit can be seen under **Stages** changes dropdown.
- Enter a commit message (a short message describing the changes).
- Click on the **Commit** button to commit the changes.
- Click on the three dots and select **Push** from the menu to publish the changes.
- Go to the product GitHub repository to check commits. 
- Open the product website to see the recently published content.

> It takes around 5-10 minutes to reflect the changes on the product website. 

  



