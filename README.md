# Practice repository to start learning Git

## Commands used

 - git init: Create a repository

 - git status: Compare working directory, staging area and current branch

 - git add: Add changes from working directory to stating area

 - git commit: Commit changes from staging area to current branch
 - git commit -m: Add the description on cmd without invoking the editor

 - git config: Set or Get configuration

 - git log: Shows the history of project commits
 - git show: Show a single commit
 - git diff: Show the difference between commits, the working directory, and the staging area.
 - git checkout: Check out branch (update HEAD and apply changes to working directory)

 - git stash: Stash changes from working directory
 - git stash list: List stashes
 - git stash pop: Apply stashed changes to working directory

## Commit messages

Default editor is vim (in my case it is nano), and it can be changed
 - `i` to enter *insert* mode inside vim
 - Then type what you need as commit message
 - `ESC` -> `:wq` -> `ENTER` to write the message and quit

...At nano, use `CRTL+X` to quit, and confirm that you want to save the changes

When writing the messages, avoid ending with `.`
And use concise, good grammar and clear information upon the changes done.


