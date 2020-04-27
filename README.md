# 2020-04-27 git basics O'Reilly Training Notes

- `git init`: create a git repository in current directory
  - you should only do this once in a repository (i.e. no nested git repos)
- `git status`: tells you what is going on

- `atom FILENAME`: creates or opens file in folder using Atom text editor

- `git add <FILENAME>`: puts file(s) to staging area
- `git commit`: commits the file with changes
  - `git commit -m "message"`: commits with message without opening up text editor
  - message should describe what changes were made

- `git log`: look at all the commit history you've been doing
  - `log --oneline`: simple one line log view
- `git diff`: look at differences between current state and what git knows

- `HEAD`: the place we're looking at right not on our computer

- remote: a place where git repo is stored (e.g. GitHub, BitBucket, GitLab)
  - `git remotre at origin <URL>`: add a remote
