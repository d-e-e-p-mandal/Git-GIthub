# Quit Commands in Git

Git itself does not have one single quit command.  
Different situations use different quit commands.

---

# 1. Quit Vim Editor in Git

Sometimes Git opens Vim for:

- merge message
- commit message
- rebase message

## Example Screen

```text
Merge branch 'main'
~
~
~
```

---

## Quit Without Saving

Press:

```text
Esc
```

Then type:

```bash
:q!
```

and press:

```text
Enter
```

---

## Save and Quit

Press:

```text
Esc
```

Then type:

```bash
:wq
```

Press:

```text
Enter
```

---

# 2. Exit Git Log

## Command

```bash
git log
```

## To Quit

```text
q
```

Just press `q`.

---

# 3. Exit Git Diff

## Command

```bash
git diff
```

## To Quit

```text
q
```

---

# 4. Abort Git Merge

If merge is stuck/conflicted:

```bash
git merge --abort
```

## Meaning

Cancels merge and returns project to previous state.

---

# 5. Abort Git Rebase

```bash
git rebase --abort
```

## Meaning

Stops rebase and restores old state.

---

# 6. Exit Detached HEAD State

## Example

```bash
git checkout commit_id
```

## To Return

```bash
git checkout main
```

---

# Most Common Quit Commands

| Situation | Command |
|---|---|
| Exit git log | `q` |
| Exit git diff | `q` |
| Quit Vim without save | `:q!` |
| Save and quit Vim | `:wq` |
| Cancel merge | `git merge --abort` |
| Cancel rebase | `git rebase --abort` |