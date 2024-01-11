# 42_vscode_terminal

`cat /app/share/vscode/flatpak-warning.txt`

VsCode : Edit in settings.json

![alt text](./settings.png)

add : 
```
    "terminal.integrated.defaultProfile.linux": "zsh",
    "terminal.integrated.profiles.linux": {
      "zsh": {
        "path": "host-spawn",
        "args": ["zsh"]
      },
      "bash": {
        "path": "host-spawn",
        "args": ["bash"]
      }
    }
```

![alt text](./settings2.png)

Restart VsCode and kill Terminal + new termial
