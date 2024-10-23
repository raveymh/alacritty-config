## Ravey's alacritty config
| OS | PATH |
| :- | :--- |
| Linux, MacOS | `$XDG_CONFIG_HOME/nvim`, `~/.config/alacritty` |
| Windows (cmd)| `%appdata%\alacritty\` |
| Windows (powershell)| `$env:APPDATA\alacritty\` |


#### Clone alacritty-config
<details><summary> Linux and Mac </summary>

```sh
git clone https://github.com/raveymh/alacritty-config.git "${XDG_CONFIG_HOME:-$HOME/.config}"/alacritty
```

</details>

<details><summary> Windows </summary>

If you're using `cmd.exe`:

```
git clone https://github.com/raveymh/alacritty-config.git "%appdata%\alacritty"
```

If you're using `powershell.exe`

```
git clone https://github.com/raveymh/alacritty-config.git "${env:APPDATA}\alacritty"
```

</details>
