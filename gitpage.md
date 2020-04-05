| [Home](README.md) | [Markdown](mdown.md)   |      [Text Editor vs (CLI) vs (IDE)](terminal.md) | [Git](gitpage.md) |[HTML](https://github.com/saifalmandeel/Learning-Journal/blob/master/folder/index.html) |

# What is Git

Git is a distributed version-control system for tracking changes in source code during software development. 
It is designed for coordinating work among programmers, but it can be used to track changes in any set of files.
Its goals include speed, data integrity, and support for distributed, non-linear workflows.

## Some Basic commands that I learned 

|   Git task    |   Notes    |   Git commands    |
|-------|-------|-------|
|    Check out a repository   |   Create a working copy of a local repository:    |  git clone /path/to/repository     |
|    Add files   |   Add one or more files to staging (index):    |   git add <filename> git add *    |
|   Commit    |   Commit changes to head (but not yet to the remote repository):    |  git commit -m "Commit message"     |
|   Commit    |  Commit any files you've added with git add, and also commit any files you've changed since then:     |   git commit -a    |
|   Push    |   Send changes to the master branch of your remote repository:    |  git push origin master     |
|   Status    |   List the files you've changed and those you still need to add or commit:    |  git status     |
|     fetch   |   command downloads commits, files, and refs from a remote repository into your local repo.    | git fetch <remote> <branch>      |
|    diff   |   See differences between local changes and master    |   git diff origin/master    |
|    pwd    |  You can easily remember this command when you know what it stands for: "print working directory"   |   git pwd    |
|    pull   |  Update the remote-tracking branches for the repository you cloned from, then merge one of them into your current branch     |  git pull     |
