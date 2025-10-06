# Git remote
- Vscode is connected to Github repo
- Vscode is remote -> Github repo

Check for currently connected remote
```Python
git remote -v
```
origin  https://github.com/seongon-agency/chatgpt-seo.git (push)

*origin* is the name of the remote.

# Git branch
- Create branches to work on different features while not affecting the main tree (yet)
- Merge the brach back to the tree (main) to implement changes once tested.

Check for branches:
```Python
git branch
```

"* main" -> 
- main is the branch's name.
- green highlighted -> we are on that branch.

## Create a new branch
Create a new branch
```Python
git branch [Branch_name]
git branch markdown_to_supabase
```

Switch to a branch
```Python
git checkout [Branch_name]
git checkout supabase_to_markdown
```

Delete a branch
```Python
git branch -d [Branch_name]
```

# Git add
- Add files to "Version"

```Python
git add .
```

(add all the current files in the folder into the snapshot)

# Git commit
- Take the snapshot

```Python
git commit -m "message"
git commit -m "added git-notes.md file"
```

# Git push
- PUsh all the changes to Github

```Python
git push [remote_name] [branch_name]

git push origin main
```