# .config-starship
My Starship.toml config file
![Example](https://github.com/user-attachments/assets/8825e931-0664-42ed-8eee-5dbda358d09e)

# Installation
## Windows

* Install `Scoop` by pasting this in a powershell prompt:
```pwsh
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
Invoke-RestMethod -Uri https://get.scoop.sh | Invoke-Expression
```
* now, install starship using scoop:
```pwsh
scoop install starship
```

## Linux

* In a terminal prompt, paste the following
```bash
curl -sS https://starship.rs/install.sh | sh
```

# Config

copy the `starship.toml` file to `~/.config/` directory.
