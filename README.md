![Logo](HIP_banner.png "Hack In Place!")


> Today we're going to learn **git**! We're going to pratice cloning, adding, commiting, merging, and resolving merge conflicts! At the end of this lab you'll have a personal webpage that you can access at https://github.com/andrewdchen/HIP-A2CN/docs/ !

# Getting Started: 

1. Cloning the repository.
```bash
git clone https://github.com/andrewdchen/HIP-A2CN.git
```
2. Making your markdown file. 
```bash
cd HIP-A2CN/docs  
touch *username*.md
```
Alternatively, you can make the markdown file via file explorer/finder.
> What is markdown? Markdown is a lightweight markup language for creating formatted text using a plain-text editor.[[1]](#1). This cheatsheet might be helpful for step 3: [Github Markdown Cheatsheet](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf)

3. Editing your markdown file.
- Use your favorite texteditor e.g. TextEdit, Vim, Sublime to add your personalized content!

4. Adding and Committing your changes.
```bash
git add *username*.md
git commit -m "*username* initial commit"
```
**Additional practice:**

`git status` is a useful command for seeing what has changed relative to your latest commit or your HEAD pointer.
- Try `git status` before and after you `git add`. What does the message say? Can you undo `git add`? 
- Try `git status` after you `git commit`, what does the message say? Can you undo `git commit`?

5. Pushing your changes.
```bash
git push origin master
```
**Additional practice:** What does origin mean? What does master mean?

6. Merge the upstream changes. 
```bash
git status
```
- `git status` also gives you instructions on what files have conflicts, and how to resolve the conflict.
- Use your favorite text editor to resolve the merge conflict.

## References
<a id="1">[1]</a> 
https://en.wikipedia.org/wiki/Markdown
