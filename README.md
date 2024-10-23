Ravey's alacritty config
| OS | PATH |
| :- | :--- |
| Linux, MacOS | `$XDG_CONFIG_HOME/nvim`, `~/.config/nvim` |
| Windows (cmd)| `%localappdata%\nvim\` |
| Windows (powershell)| `$env:LOCALAPPDATA\nvim\` |


#### Clone alacritty-config
<details><summary> Linux and Mac </summary>

```sh
git clone https://github.com/raveymh/alacritty-config.git "${XDG_CONFIG_HOME:-$HOME/.config}"/nvim
```

</details>

<details><summary> Windows </summary>

If you're using `cmd.exe`:

```
git clone https://github.com/raveymh/alacritty-config.git "%localappdata%\nvim"
```

If you're using `powershell.exe`

```
git clone https://github.com/raveymh/alacritty-config.git "${env:LOCALAPPDATA}\nvim"
```

</details>
