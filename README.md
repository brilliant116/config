
#### alacritty

用户配置文件为`~/.config/alacritty/alacritty.yml`

#### kitty

用户配置文件为`~/.config/kitty/kitty.conf`

#### VS Code

用户配置文件为`~/.config/Code/User/settings.json`

#### nano的配置

```
cp /etc/nanorc ~/.config/nano/nanorc
```

nano-syntax-highlighting安装

```
sudo pacman -S nano-syntax-highlighting
```

```
~/.config/nano/nanorc
---------------------
include "/usr/share/nano/*.nanorc"
include "/usr/share/nano-syntax-highlighting/*.nanorc"
```

#### ranger

```
sudo pacman -S ranger
```

手动生成配置文件

```
ranger --copy-config=all
```
