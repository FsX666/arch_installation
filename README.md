# arch installation

## ajout de flameshot

`sudo pacman -Sy flameshot`

## ajout de rofi-greenclip

`sudo pacman -Sy rofi && yay -S rofi-greenclip && systemctl enable --user greenclip && systemctl start --user greenclip`

### modification du theme

utiliser le theme se trouvant dans le repository sous le nom de Monokai_by_FsX.rasi qu'il faudra placer dans le répertoire /usr/share/rofi/themes
