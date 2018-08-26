
#### Mac
```bash
git config --global core.excludesfile ~/tools/global-git-ignore/.gitignore
```

#### Windows
```bash
git config --global core.excludesfile %USERPROFILE%\.gitignore
```

This will result in an entry in your .gitconfig that looks like this:
```bash
[core]
    excludesfile = {path-to-home-dir}/.gitignore
```

## Global .gitignore contents
