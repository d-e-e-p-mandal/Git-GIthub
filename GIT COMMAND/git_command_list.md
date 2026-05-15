# Complete Git Commands Syllabus

# 1. Git Introduction Commands
- git --version
- git help
- git help command-name
- which git
- where git

---

# 2. Git Configuration Commands
- git config
- git config --global
- git config --local
- git config --system
- git config --list
- git config --show-origin
- git config --unset
- git config user.name
- git config user.email

---

# 3. Repository Creation Commands
- git init
- git init -b
- git init --bare
- git clone
- git clone --bare
- git clone --mirror
- git clone --depth
- git clone -b

---

# 4. Repository Information Commands
- git status
- git status -s
- git rev-parse
- git show-ref
- git symbolic-ref
- git count-objects

---

# 5. File Tracking Commands
- git add
- git add .
- git add -A
- git add -u
- git add -p
- git restore
- git restore --staged

---

# 6. Commit Commands
- git commit
- git commit -m
- git commit -a
- git commit --amend
- git commit --amend -m

---

# 7. Commit History Commands
- git log
- git log --oneline
- git log --graph
- git log --all
- git log --stat
- git log -p
- git show
- git reflog

---

# 8. Difference Commands
- git diff
- git diff --staged
- git diff commit1 commit2
- git diff branch1 branch2
- git diff --name-only

---

# 9. Undo & Recovery Commands
- git reset
- git reset --soft
- git reset --mixed
- git reset --hard
- git revert
- git restore
- git checkout
- git reflog
- git fsck

---

# 10. File Removal Commands
- git rm
- git rm -f
- git rm -r
- git rm --cached

---

# 11. Rename & Move Commands
- git mv

---

# 12. Branch Commands
- git branch
- git branch -a
- git branch -r
- git branch -v
- git branch -d
- git branch -D
- git branch -m
- git branch --merged
- git branch --no-merged
- git branch --show-current
- git branch --track
- git branch --set-upstream-to
- git branch --unset-upstream

---

# 13. Branch Switching Commands
- git checkout
- git checkout -b
- git checkout -
- git switch
- git switch -c

---

# 14. Merge Commands
- git merge
- git merge --no-ff
- git merge --squash
- git merge --abort
- git merge --continue
- git mergetool

---

# 15. Merge Conflict Commands
- git status
- git diff
- git add
- git merge --abort
- git merge --continue
- git mergetool

---

# 16. Remote Repository Commands
- git remote
- git remote -v
- git remote add
- git remote remove
- git remote rename
- git remote show
- git remote set-url

---

# 17. Push Commands
- git push
- git push origin main
- git push -u origin main
- git push --all
- git push --tags
- git push --force
- git push --force-with-lease
- git push origin --delete

---

# 18. Pull Commands
- git pull
- git pull origin main
- git pull --rebase

---

# 19. Fetch Commands
- git fetch
- git fetch origin
- git fetch --all
- git fetch --tags

---

# 20. Tag Commands
- git tag
- git tag -a
- git tag -d
- git push --tags
- git push origin --delete

---

# 21. Stash Commands
- git stash
- git stash save
- git stash list
- git stash apply
- git stash pop
- git stash drop
- git stash clear

---

# 22. Rebase Commands
- git rebase
- git rebase -i
- git rebase --continue
- git rebase --abort
- git rebase --skip

---

# 23. Cherry-Pick Commands
- git cherry-pick
- git cherry-pick --continue
- git cherry-pick --abort

---

# 24. Clean Commands
- git clean
- git clean -f
- git clean -fd
- git clean -fx
- git clean -n

---

# 25. Repository Maintenance Commands
- git gc
- git gc --aggressive
- git prune
- git repack
- git prune-packed
- git fsck

---

# 26. Backup & Archive Commands
- git bundle
- git archive
- git archive --format zip
- git archive --format tar

---

# 27. Object Inspection Commands
- git cat-file
- git verify-pack
- git count-objects

---

# 28. Search & Inspection Commands
- git grep
- git blame
- git bisect
- git show

---

# 29. Submodule Commands
- git submodule add
- git submodule init
- git submodule update
- git submodule foreach

---

# 30. Worktree Commands
- git worktree add
- git worktree list
- git worktree remove

---

# 31. Alias Commands
- git config --global alias.st
- git config --global alias.co
- git config --global alias.br
- git config --global alias.cm
- git config --global alias.lg

---

# 32. Hook Commands
- pre-commit
- post-commit
- pre-push
- post-merge

---

# 33. Debugging Commands
- GIT_TRACE=1
- GIT_TRACE_PACKET=1
- git var -l

---

# 34. Security Commands
- git verify-commit
- git verify-tag
- git config credential.helper

---

# 35. Git LFS Commands
- git lfs install
- git lfs track
- git lfs pull
- git lfs push

---

# 36. Git Flow Commands
- git flow init
- git flow feature start
- git flow feature finish
- git flow release start
- git flow hotfix start

---

# 37. GitHub CLI Commands
- gh auth login
- gh repo create
- gh repo clone
- gh pr create
- gh pr merge

---

# 38. SSH Commands for Git
- ssh-keygen
- ssh-add
- ssh -T git@github.com

---

# 39. Git Ignore Commands
- .gitignore
- git check-ignore

---

# 40. Patch Commands
- git format-patch
- git apply
- git am

---

# 41. Sparse Checkout Commands
- git sparse-checkout init
- git sparse-checkout set

---

# 42. Credential Commands
- git credential fill
- git credential approve
- git credential reject

---

# 43. Networking Commands
- git daemon
- git request-pull
- git instaweb

---

# 44. Server Commands
- git init --bare
- git daemon
- git update-server-info

---

# 45. Advanced Git Commands
- git filter-branch
- git replace
- git notes add
- git notes show
- git notes remove
- git rerere

---

# 46. Git Internal Commands
- git hash-object
- git update-index
- git write-tree
- git commit-tree
- git rev-list

---

# 47. Git Workflow Models
- Feature Branch Workflow
- Git Flow Workflow
- Forking Workflow
- Trunk-Based Workflow

---

# 48. Git Best Practices
- Frequent Commits
- Small Branches
- Pull Before Push
- Clear Commit Messages
- Conflict Prevention
- Branch Naming Standards
- Repository Cleanup

---

# 49. Git Architecture Topics
- Working Directory
- Staging Area
- Local Repository
- Remote Repository
- HEAD Pointer
- Refs
- Index
- Reflog

---

# 50. Git Troubleshooting Topics
- Merge Conflicts
- Detached HEAD
- Lost Commits
- Broken Rebase
- Push Rejections
- Authentication Errors
- Repository Corruption
