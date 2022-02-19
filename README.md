# arch installation

## ajout de flameshot

`sudo pacman -Sy flameshot`

## ajout de rofi-greenclip

`sudo pacman -Sy rofi && yay -S rofi-greenclip && systemctl enable --user greenclip && systemctl start --user greenclip`

### modification du theme

utiliser le theme se trouvant dans le repository sous le nom de Monokai_by_FsX.rasi qu'il faudra placer dans le répertoire /usr/share/rofi/themes

Puis ajouter dans la configuration de i3:

`bindsym control+space exec --no-startup-id rofi -modi "clipboard:greenclip print" -show clipboard`

## Installation des polices Nerd

`sudo mkdir -p /usr/local/share/fonts && sudo cp *.ttf /usr/local/share/fonts/ && sudo fc-cache`


