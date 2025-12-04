# Productivity-App
chigga chigga chigga jeremy icebergus digolas

## Git commands for normal changes to main build
1. Stage changes using `git add (file name)` to add changes to a file or `git add .` to add all changes.
2. Commit changes using `git commit -m "commit comment here."`
3. Push changes to the remote server using `git push (remote name) (branch name)`. To push to the main branch, use `git push origin main`.

## Other remote commands
1. Use `git fetch origin` to locally download all the changes that have been made in the repo.
2. Use `git clone https://github.com/Nicolasshang/Productivity-App` to get a local copy of the repo.
3. Use `git status` or `git log --oneline` to check stuff in general and `git remote` to check for remotes.

## Branching
1. Use `git checkout -b [branch name]` to create a new branch and go onto it. Use `git checkout [branch name]` to just navigate to that branch.
2. Running `git -a -m "commit message"` will auto-commit all changes in the branch you're on.
3. For merging into main, checkout into main and run `git merge [branch name]`
4. `git pull origin main` first fetches all the changes from the main branch, integrates it into your current branch, and then merges them together. 

CHIGGOLAS SHANG