![Logo](HIP_banner.png "Hack In Place!")


> Today we're going to learn **git**! We're going to pratice cloning, adding, commiting, merging, and resolving merge conflicts! At the end of this lab you'll have a personal webpage that you can access at https://andrewdchen.github.io/HIP-A2CN/docs/ !

# Getting Started: 

### 1. Forking the repository. 
- On Github:
  - Look for the Fork button at the top right of the page, it should look like this:
  <img src="https://github-images.s3.amazonaws.com/help/bootcamp/Bootcamp-Fork.png" width="350">

### 2. Cloning your forked repository.
- **On Github:**
  - To clone your respository find the green `Code` button and copy the https link. Make sure you are cloning your version of this repository, not this one. The clone button should look like: 
  <img src="https://docs.github.com/assets/images/help/repository/code-button.png" width="350">

- **On your terminal:** 
```bash
git clone <url for your fork>
```
### 3. Checking out a new branch!
- **On your terminal:** 
```bash
git checkout -b <branchname>
```
- We're about to make some changes so let's checkout a new branch!

### 4. Making your markdown file. 
- **On your terminal:** 
```bash
cd HIP-A2CN/docs  
touch *username*.md
```
Alternatively, you can make the markdown file via file explorer/finder.

> What is markdown? Markdown is a lightweight markup language for creating formatted text using a plain-text editor.[[1]](#1). This cheatsheet might be helpful for step 3: [Github Markdown Cheatsheet](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf)

### 5. Editing your markdown file.
- Use your favorite texteditor e.g. TextEdit, Vim, Nano, Sublime to add your personalized content!

### 6. Adding and Committing your changes.
- **On your terminal:** 
```bash
git add *username*.md
git commit -m "*username* initial commit"
```
**Additional practice:**

`git status` is a useful command for seeing what has changed relative to your latest commit or your HEAD pointer.
- Try `git status` before and after you `git add`. What does the message say? Can you undo `git add`? 
- Try `git status` after you `git commit`, what does the message say? Can you undo `git commit`?

### 7. Pushing your changes.
- **On your terminal:** 
```bash
git push origin <branch_name>
```
**Additional practice:** What does origin mean? What does master mean?

### 8. Create a pull request.
- **On Github:**
- More instructions here: [Creating a pull request from a fork](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request-from-a-fork)
- For step 6, make sure the upstream repository is `andrewdchen/HIP-A2CN`, and the downstream repository is your own with the branch you made just now!
- Once you finish step 8, let a TA know in the chat!

### 9. Resolve the merge conflict
- Find your pull request here: https://github.com/andrewdchen/HIP-A2CN/pulls, and resolve the conflict!
- Once you have resolved the conflict, commit the change, and let a TA know in the chat! We will incorporate your pull request and you will be able to see your website at https://andrewdchen.github.io/HIP-A2CN/docs/<nameofdocument>

## References
<a id="1">[1]</a> 
https://en.wikipedia.org/wiki/Markdown
