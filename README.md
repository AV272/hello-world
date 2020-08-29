# hello-world
Base commands and code for github

# 1. Gitignore
You can create `.gitignore` file which not add some file from repo to gitcloud.
You can automaticly generate `.gitignore` file in website [gitignore.io](https://www.toptal.com/developers/gitignore).

For example for Linux:
```
# Created by https://www.toptal.com/developers/gitignore/api/linux
# Edit at https://www.toptal.com/developers/gitignore?templates=linux

### Linux ###
*~

# temporary files which can be created if a process still has a handle open of a deleted file
.fuse_hidden*

# KDE directory preferences
.directory

# Linux trash folder which might appear on any partition or disk
.Trash-*

# .nfs files are created when an open file is removed but is still being accessed
.nfs*

# End of https://www.toptal.com/developers/gitignore/api/linux

```

# 2. Markdown
Github guide on markdown:
* [https://guides.github.com/features/mastering-markdown/]

# 3. Connecting to github with SSH
* [https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh]

# 4. Base commands for git terminal

1. `git init`  -- initialisation of the folder in computer (create .git folder)
2. `git add <filename>`  -- adding file to .git folder (not to gitcloud)
3. `git commit -m "comment" <filename or -a(all)>`  -- fix changes in files with comment (not in gitcloud)
4. `git push origin master`  --send changes to git cloud. "origin" - local folder name on computer, 
"master" - branch in gitcloud file in which send changes.
