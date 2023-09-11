# 2023-09-11_git_history

- `add <filename>`: adding filenames to the staging area
- `commit -m "MESSAGE"`: commit with message everything in the staging area 
- `push <WHERE> <WHAT>`: push from local to remote repository
- `pull <WHERE> <WHAT>`: pull from remote (where) to local repository using the info in the specified branch (what)

- `log`: shows the log
    - `log --oneline`: shows the log in condensed format
    - if there are too many commits to show on the terminal, the terminal will show `:`, allowing you to scroll up and down but preventing further commands
        - press `q` to quit

- `diff <FILENAME>`: shows the difference between your changes and the last known git state
    - `diff --staged`: shows you the diff of the files in the staging area
    - `diff <FILENAME>`: shows diff for a specific file

- `restore --staged <FILE>`: unstages <FILE> from the staging area

- `.gitignore`: specifies files or patterns (regex) to be ignored by git
    - templates exist for each language that can be combined
    - often good practice to ignore output from code

Here's some information I don't want to be here