# arch installation

## Installation de base

`sudo pacman -Sy bash-completion bind binutils blueman bluez-utils btrfs-progs cantarell-fonts certbot chromium clamav clamtk code dmidecode docker dos2unix dosfstools ecryptfs-utils etcher ethtool filezilla firefox gimp gnome-keyring gparted gufw htop httpie icedtea-web iftop ipcalc keepassxc mailutils mtr ncdu net-tools nfs-utils nmap ntp netcat pdftk pgadmin4 postfix pulseaudio-bluetooth pwgen rdesktop rsync screen sslscan strace tcpdump terminator ttf-meslo-nerd-font-powerlevel10k ttf-nerd-fonts-symbols vim virt-manager virtualbox vlc whois wireshark-qt x11-ssh-askpass xorg-xsetroot`

`yay -S aur/nomachine && yay -S aur/openvpn-update-systemd-resolved && yay -S aur/synology-drive`

`sudo pacman -Rns palemoon-bin clipit nano`

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


