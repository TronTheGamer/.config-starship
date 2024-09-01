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

* Add the following to your `$PROFILE` file:
```pwsh
Invoke-Expression (&starship init powershell)
``

## Linux

* In a terminal prompt, paste the following
```bash
curl -sS https://starship.rs/install.sh | sh
```
* If you use `bash`, add the folllowing line to the end of `.bashrc` file:
  ```bash
  eval "$(starship init bash)"
  ```
* if `fish` then add the following to the `~/.config/fish/config.fish`
```fish
starship init fish | source
```

* If `zsh` then add the following to your `~/.zshrc` file:
```zsh
eval "$(starship init zsh)"
```

# Config

* copy the `starship.toml` file to `~/.config/` directory.

