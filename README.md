## Windows XP Theme

- Wallpaper: Bliss
- GTK/Icons: [B00merang](https://b00merang.weebly.com/icon-themes.html)
- WM theme: [RedmondXP](https://github.com/matthewmx86/RedmondXP)

### Requirements

- xfce4
- xfce4-goodies
- xfce4-whiskermenu-plugin

for debian based you can use `apt`:
```bash
sudo apt-get install xfce4 xfce4-goodies xfce4-whiskermenu-plugin
```

### Instruction

1. Decompress all compressed file
    ```bash
    tar xzvf Windows-XP-3.1-theme.tar.gz
    tar xzvf Windows-XP-3.1-icon.tar.gz
    ```
2. Move Windows-XP-3.1-theme to `~/.themes` directory
    ```bash
    mv Windows-XP-3.1-theme ~/.themes
    export GTK_OVERLAY_SCROLLING=0
    ```
3. Move Windows-XP-3.1-icon to `~/.icons` directory
    ```bash
    mv Windows-XP-3.1-icon ~/.icons
    ```
4. Setting icon and theme in appearance
