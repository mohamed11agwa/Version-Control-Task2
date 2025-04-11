# Removing Git Branches
## Delete  Local Branch
```
git branch -d branch-name
```
## Delete  remote Branch

```
git push origin --delete branch-name
```
# Git Tags
## Annotated Tags vs Lightweight Tags

### Annotated Tags:
  - Stored as full objects in Git.
  - Can include message, tagger name, email, and date.
  - Used for official releases.
  - Created with: `git tag -a v1.0 -m "message"`

### Lightweight Tags:
  - Just a reference to a commit (like a branch).
  - No extra metadata.
  - Created with: `git tag v1.0`


## When to Use Rebase?

When you want to write your code without worrying about breaking it up into isolated commits.

You want to fixup commits before merging.


## How to List Tags?

```
git tag
```
# Delete Tag Locally and Remotely
## Delete a Local Tag

```
git tag -d v1.0
```
## Delete a Remote Tag
```
git push origin --delete v(tag_version)
```

![My Project Banner](images/git.webp)
