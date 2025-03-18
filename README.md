# GitHub Actions
Reusable GitHub Actions for various purposes.

### Useful git tag commands
Deleting an existing tag locally:
```bash
git tag -d <tag_name>
```

Deleting an existing tag from the remote repository:
```bash
git push origin --delete <tag_name>
```

Creating a new tag on the latest commit locally:
```bash
git tag <tag_name>
```

Creating a new tag on the specific commit locally:
```bash
git tag <tag_name> <commit_hash>
```

After creating the new tag locally, you can push it to the remote repository:
```bash
git push origin <tag_name>
```

