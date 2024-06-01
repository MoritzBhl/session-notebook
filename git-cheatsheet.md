Commands for branches

git switch -c <branchname> -> create a new branch and switch to it
git switch <branchname> -> switch branches
git branch -> list your branches
git branch -a -> list all branches (local and remote)
git branch -d <branchname> -> deletes a branch
git push -u origin <branchname> -> pushes the new branch and the changes (it is not possible to push just a new branch)

Core commands

git init [directory] -> Creates new local repository
git clone [repo] -> Creates local copy of remote repository
git add [directory] -> Stages specific [directory]
git add [file] -> Stages specific [file]
git add -A -> Stages all changed files
git add . -> Stages new and changed files, NOT deleted files
git add -u -> Stages changed and deleted files, NOT new files
git commit -m "[message]" -> Commit everything that is staged
git status -> Shows status of changes as untracked, modified or staged
