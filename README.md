# 2023-09-11-git_history


- `add <FILENAMES>`: adding the ... to the staging area
- `commit -m "MESSAGE"`: commit with a message everything in the staging area
- `push <WHERE> <WHAT>`: pushes the history/commits to the remote (where)using the commits from the specified branch (what)
- `pull <WHERE> <WHAT>`: pulls (updates)

- `log`: shows the log
  - `log --oneline`: shows the log in condenced format
  - `

- `git diff`: shows you the "difference" between your changes and the last known git state
  - `diff --staged`: shows you the diff of the files in the staging area
  - `restore --staged <FILE>`: unstages <FILE> from the staging area

  - `revert <SHA1>`: undos the changes in the commit specified in `<SHA1>`

  - test git diff
  - test git diff again with git stash

  - that's how git diff works

