# github-3.1-nasir
## Setup & Init
- git init | To initialize existing directory as a Git Repository |
- git clone [url] | retrieve an entire repository from a hosted location via URL|

## Stage & Snapshot
- git status | show modified files in working directory, staged for next commit |
- git add[file] | add a file as it looks now to your next commit(stage) |
- git reset [file] | unstage a file while retaining the changes in working directory |
- git diff | diff of what is changed but not staged
- git diff --staged | diff of what is staged but not yet committed |
- git commit -m "[descriptive message]" | commit your staged content as a new commit snapshot |

## Branch & Merge
- git branch    |   list your branches. a* will appear next to the currently active branch
- git branch [branch-name]  |   create a new branch at the current commit
- git checkout  |   switch to another branch and check it out into your working directory
- git merge [branch]    |   merge the specified branch's history into the current one
- git log   |   show all commits in the current branch's history
