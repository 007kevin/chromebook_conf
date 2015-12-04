#backup X11
mkdir ~/backup
sudo mv /usr/share/X11/xorg.conf.d/* ~/backup

copy *.conf to /usr/share/X11/xorg/conf.d

#Change keyboard layout
sudo sed -i 's/gb/us/g' 10-keyboard.conf
