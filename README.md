# BASICS
## MD Syntax
MD is a common way to address simple documentation (e.g. README) or content pages. A primer on its syntax can be found [here](https://github.com/tchapi/markdown-cheatsheet/blob/master/README.md "Markdown Cheatsheet")

## Git basics
Git was "invented" by Linus Torvalds to manage the growing complexity of the Linux kernel. A primer on its capabilities is [https://rogerdudler.github.io/git-guide/]

For example, to update this file, what I did was:
- clone the repos on my computer `git clone https://github.com/iSassiUK/learning_http.git`
  - you probably don't need that
- edit the README.md (I am using Geany)
- inside learning_http:
  - `git add README.md` I modified this file; everything logically related has to be added to a commit
  - `git commit -m 'README.md +Some basics about GIT and MD'` Not yet on the sever, only on client
  - `git push` Now it's on the server!

And now you see this new version of the README! This add-commit-push can be done using a GUI or via command line



