[Setting Username and Email]()


# Username:

**Purpose**
- Git records the username in every commit.

## Set Global Username

```bash
git config --global user.name "Deep Mandal"
```

- This username applies to all repositories for the current user.


## Set Local Username

*Inside repository:*

```bash
git config user.name "Project User"
```

- This username applies only to that repository.


# Setting Email

**Purpose:**
- Git records the email address in commits.s

## Set Global Email

```bash
git config --global user.email "deep@gmail.com"
```

## Set Local Email

```bash
git config user.email "project@gmail.com"
```
- Applies only to the current repository.



# Checking Git Configuration

## View All Configurations

```bash
git config --list
```

Shows:
- Username
- Email
- Editor
- Aliases
- Other settings

---

## Check Specific Configuration

### Check Username

```bash
git config user.name
```

### Check Email

```bash
git config user.email
```

---

## Check Global Configuration

```bash
git config --global --list
```

---

## Check Local Configuration

Inside repository:

```bash
git config --local --list
```

---

# Global vs Local Configuration

# Global Configuration

## Meaning

Global configuration applies to:
- All repositories of the current user

Stored in:

```text
~/.gitconfig
```

---

## Example

```bash
git config --global user.name "Deep"
```

All repositories will use this username unless overridden locally.

---

# Local Configuration

## Meaning

Local configuration applies only to:
- Current repository

Stored in:

```text
project/.git/config
```

---

## Example

```bash
git config user.name "Project User"
```

Only that repository uses this username.

---

# Difference Between Global and Local

| Feature | Global | Local |
|---|---|---|
| Scope | All repositories | Current repository |
| Storage Location | ~/.gitconfig | .git/config |
| Command | --global | Default/local |
| Priority | Lower | Higher |

---

# Example Scenario

Suppose:

Global username:

```text
Deep Mandal
```

But for company project:

```text
Company Developer
```

You can set:
- Global for personal projects
- Local for company repository

Git will use:
- Local configuration inside that repo
- Global configuration elsewhere