# github-3.1-your-zaw
## Setup & Init
|- git init | To initialize existing directory as a Git Repository |
|- git clone [url] | retrieve an entire repository from a hosted location via URL|

## Stage & Snapshot
- git status | show modified files in working directory, staged for next commit |
- git add[file] | add a file as it looks now to your next commit(stage) |
- git reset [file] | unstage a file while retaining the changes in working directory |
- git diff | diff of what is changed but not staged
git diff --staged | diff of what is staged but not yet committed |
- git commit -m "[descriptive message]" | commit your staged content as a new commit snapshot |