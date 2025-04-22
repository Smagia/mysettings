# 🛠️ Smagia's Git Config

A minimal and practical Git configuration focused on everyday speed and clean workflows.

## 🔧 Configuration

This `.gitconfig` file includes:

### ✅ User Info

```ini
[user]
  name = <name>
  email = <email>
```

### ⚡️ Aliases
| Alias | Expands To         | Description                  |
|-------|--------------------|------------------------------|
| a     | add                | Stage changes                |
| ai    | add -i             | Interactive staging          |
| sa    | stash              | Save current changes         |
| sal   | stash list         | List saved stashes           |
| sap   | stash pop          | Reapply last stash           |
| st    | status             | Show working directory status|
| c     | checkout           | Switch branches              |
| cb    | checkout -b        | Create and switch branches   |
| m     | checkout master    | Jump to master branch        |
| cm    | commit -m          | Commit with message          |
| f     | fetch              | Fetch remote changes         |
| p     | pull               | Pull latest changes          |
