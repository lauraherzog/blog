# Squash commits

If you want to squash all your commits to a single commit for a way cleaner merge process you simply have to do this:

```
git checkout yourBranch
git reset $(git merge-base master $(git branch --show-current))
git add -A
git commit -m "one commit on yourBranch"
```
