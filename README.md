# gitea theme yelow
Customized arc-green theme for Gitea

# Preview
![](preview/1.png)

![](preview/2.png)

# How to use:
1. Find your gitea custom directory path in ***Site Administration > Configuration > Custom File Root Path***.
2. Copy directory: ***public/*** into this path
3. Add folowing lines to your gitea config:
```ini
[ui]
THEMES = gitea,arc-green,yelow
DEFAULT_THEME = yelow
```
4. Restart your Gitea Service and you are ready to go.
