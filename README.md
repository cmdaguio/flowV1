# Git workflow V1

1. `mkdir <local_repo>`
2. cd <local_repo>`
3. `git init`
4. create new repo in github with same name as local repo, add .gitignore and license
5. `git add remote origin <remote_repo>
6. `git pull --set-upstream origin main` (This will pull all changes in remote repo, and also track it. See `git status`)
7. `git push` (Great! You can now push changes you've made in the local repo)\

**ALTERNATIVE STEPS (If you made changes in the local repo)**
6. `git pull --rebase origin` (Pull changes from remote repo, plus rebase local repo on top of the remote repo)
7. `git branch -u origin main` (This tells your local repo to track the remote repo. See `git status`)
8. `git push` (Nice--you can now send changes to your github. Happy coding!!!)

PS Make sure to add and commit your changes before pushing!
