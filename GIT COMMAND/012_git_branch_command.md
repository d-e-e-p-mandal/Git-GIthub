# Git Branch Commands Notes with Examples

# git branch

```bash
git branch
```

## Explanation
- Shows all local branches in repository.
- Current branch marked using `*`.

## Example

```bash
git branch
```

### Output

```text
* main
  dev
  feature-login
```

---

# git branch -a

```bash
git branch -a
```

## Explanation
- Shows all local and remote branches.
- Useful for viewing complete branch list.

## Example

```bash
git branch -a
```

### Output

```text
* main
  dev
  remotes/origin/main
  remotes/origin/dev
```

---

# git branch -r

```bash
git branch -r
```

## Explanation
- Displays only remote branches.
- Remote branches usually come from GitHub/server.

## Example

```bash
git branch -r
```

### Output

```text
origin/main
origin/dev
origin/feature-login
```

---

# git branch -v

```bash
git branch -v
```

## Explanation
- Shows branch names with latest commit details.
- Displays commit hash and message.

## Example

```bash
git branch -v
```

### Output

```text
* main           a12bc34 Add login page
  feature-login  b45de67 Fix navbar issue
```

---

# git branch -d

```bash
git branch -d branch-name
```

## Explanation
- Safely deletes local branch.
- Branch must already be merged.

## Example

```bash
git branch -d feature-login
```

### Output

```text
Deleted branch feature-login
```

---

# git branch -D

```bash
git branch -D branch-name
```

## Explanation
- Force deletes branch.
- Deletes even if branch not merged.

## Example

```bash
git branch -D feature-login
```

### Output

```text
Deleted branch feature-login (forced)
```

---

# git branch -m

```bash
git branch -m new-branch-name
```

## Explanation
- Renames current branch.
- Keeps commit history unchanged.

## Example

```bash
git branch -m development
```

### Output

```text
Branch renamed successfully
```

---

# git branch --merged

```bash
git branch --merged
```

## Explanation
- Shows branches already merged into current branch.
- Useful for cleanup.

## Example

```bash
git branch --merged
```

### Output

```text
* main
  feature-login
```

---

# git branch --no-merged

```bash
git branch --no-merged
```

## Explanation
- Displays branches not yet merged.
- Helps identify unfinished work.

## Example

```bash
git branch --no-merged
```

### Output

```text
feature-payment
feature-dashboard
```

---

# git branch --show-current

```bash
git branch --show-current
```

## Explanation
- Shows current active branch name only.
- Simple branch checking command.

## Example

```bash
git branch --show-current
```

### Output

```text
main
```

---

# git branch --track

```bash
git branch --track local-branch origin/remote-branch
```

## Explanation
- Creates local branch connected with remote branch.
- Enables automatic tracking.

- This command creates a new local branch and connects it to a remote branch.

##### After connection:
* git pull knows where to pull from
* git push knows where to push

## Example

```bash
git branch --track dev origin/dev
```

### Output

```text
Branch 'dev' set up to track remote branch 'dev'
```


##### What Happens?

* Creates local branch → dev
* Connects it with remote branch → origin/dev

##### Visual Understanding:
```text
Remote Branch        Local Branch
origin/dev   <----->   dev
```

##### When Used:
Fort this sort command to specify origin.
- git pull
- git push
---

# git branch --set-upstream-to

```bash
git branch --set-upstream-to=origin/main
```

## Explanation
- Manually connects local branch to remote branch.
- Used for pull/push tracking.

- This command connects an existing local branch to a remote branch.
- Used when branch already exists but tracking is missing.

## Example
```
Local branch  : main
Remote branch : origin/main
```

```bash
git branch --set-upstream-to=origin/main
```

### Output

```text
Branch 'main' set up to track 'origin/main'
```
##### Interal Visulaization:
```
main   <----->   origin/main
```
---

# git branch --unset-upstream

```bash
git branch --unset-upstream
```

## Explanation
- Removes connection between local branch and remote branch.
- Removes upstream tracking branch.
- Stops automatic remote association.

```text
main  <-----> origin/main
```

## Example

```bash
git branch --unset-upstream
```

### Output

```text
Upstream tracking removed
```

##### Interak Visulazation:
```text
main      origin/main
(no connection)
```
---

# Complete Branch Workflow Example

```bash
git checkout -b feature-login
git add .
git commit -m "Add login feature"
git checkout main
git merge feature-login
git branch -d feature-login
```

---

# Branch Command Summary

| Command | Purpose |
|---|---|
| git branch | Show local branches |
| git branch -a | Show all branches |
| git branch -r | Show remote branches |
| git branch -v | Show branch details |
| git branch -d | Safe branch delete |
| git branch -D | Force branch delete |
| git branch -m | Rename branch |
| git branch --merged | Show merged branches |
| git branch --no-merged | Show unmerged branches |
| git branch --show-current | Show current branch |
| git branch --track | Track remote branch |
| git branch --set-upstream-to | Set upstream branch |
| git branch --unset-upstream | Remove upstream branch |