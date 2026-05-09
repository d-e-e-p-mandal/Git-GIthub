# Complete Git Commands Syllabus

# 1. Git Installation Commands
- git --version
- git help
- which git
- where git

---

# 2. Git Configuration Commands
- git config
- git config --global
- git config --local
- git config --system
- git config --list
- git config --unset
- git config --show-origin

---

# 3. Repository Creation Commands
- git init
- git init -b
- git init --bare
- git clone
- git clone --bare
- git clone --mirror

---

# 4. Repository Information Commands
- git status
- git remote -v
- git branch
- git branch -a
- git branch -r
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

# 9. Undo Commands
- git reset
- git reset --soft
- git reset --mixed
- git reset --hard
- git revert
- git checkout
- git restore

---

# 10. File Removal Commands
- git rm
- git rm -f
- git rm -r
- git rm --cached

---

# 11. File Rename & Move Commands
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
- git merge --abort
- git merge --continue
- git add
- git mergetool

---

# 16. Remote Repository Commands
- git remote
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
- git push origin --delete

---

# 18. Pull & Fetch Commands
- git pull
- git pull origin main
- git fetch
- git fetch --all
- git fetch --tags

---

# 19. Tag Commands
- git tag
- git tag -a
- git tag -d
- git push --tags
- git push origin --delete

---

# 20. Stash Commands
- git stash
- git stash save
- git stash list
- git stash apply
- git stash pop
- git stash drop
- git stash clear

---

# 21. Rebase Commands
- git rebase
- git rebase -i
- git rebase --continue
- git rebase --abort
- git rebase --skip

---

# 22. Cherry-Pick Commands
- git cherry-pick
- git cherry-pick --continue
- git cherry-pick --abort

---

# 23. Clean Commands
- git clean
- git clean -f
- git clean -fd
- git clean -fx
- git clean -n

---

# 24. Repository Maintenance Commands
- git gc
- git gc --aggressive
- git prune
- git fsck

---

# 25. Repository Backup Commands
- git bundle
- git archive
- git archive --format zip
- git archive --format tar

---

# 26. Object Inspection Commands
- git cat-file
- git verify-pack
- git count-objects

---

# 27. Search Commands
- git grep
- git bisect
- git blame

---

# 28. Collaboration Commands
- git pull
- git push
- git fetch
- git merge
- git rebase
- git branch -a

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

# 31. Git Alias Commands
- git config --global alias.name

---

# 32. Git Hooks Commands
- pre-commit
- post-commit
- pre-push
- post-merge

---

# 33. Git Debugging Commands
- GIT_TRACE=1
- GIT_TRACE_PACKET=1
- git var -l

---

# 34. Git Security Commands
- git verify-commit
- git verify-tag
- git config credential.helper

---

# 35. Git Large File Commands
- git lfs install
- git lfs track
- git lfs pull
- git lfs push

---

# 36. Git Workflow Commands
- git flow init
- git flow feature start
- git flow feature finish
- git flow release start
- git flow hotfix start

---

# 37. GitHub Related Commands
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

# 40. Advanced Git Commands
- git reflog
- git bisect
- git filter-branch
- git replace
- git notes
- git rerere

---

# 41. Git Recovery Commands
- git reflog
- git fsck
- git reset
- git checkout
- git restore

---

# 42. Git Inspection Commands
- git show
- git log
- git diff
- git blame
- git grep

---

# 43. Git Performance Commands
- git gc
- git repack
- git prune-packed

---

# 44. Git Networking Commands
- git daemon
- git instaweb
- git request-pull

---

# 45. Git Server Commands
- git init --bare
- git daemon
- git update-server-info

---

# 46. Git Patch Commands
- git format-patch
- git apply
- git am

---

# 47. Git Notes Commands
- git notes add
- git notes show
- git notes remove

---

# 48. Git Replace Commands
- git replace
- git replace -d

---

# 49. Git Sparse Checkout Commands
- git sparse-checkout init
- git sparse-checkout set

---

# 50. Git Credential Commands
- git credential fill
- git credential approve
- git credential reject

---

# 51. Git Workflow Models
- Feature Branch Workflow
- Git Flow Workflow
- Forking Workflow
- Trunk-Based Development

---

# 52. Git Best Practices
- Frequent Commits
- Small Branches
- Pull Before Push
- Clear Commit Messages
- Branch Naming Standards
- Conflict Prevention
- Repository Cleanup

---

# 53. Git Internal Concepts
- Blob Objects
- Tree Objects
- Commit Objects
- Tag Objects
- HEAD Pointer
- Index
- Refs
- Reflog

---

# 54. Git Architecture
- Working Directory
- Staging Area
- Local Repository
- Remote Repository

---

# 55. Git Troubleshooting
- Merge Conflicts
- Detached HEAD
- Lost Commits
- Broken Rebase
- Push Rejections
- Authentication Errors

```