# Linux Desktop Wallpapers for PS5

Custom PS5 wallpapers collection for Linux desktop systems such as Ubuntu 26.04.

## Installation
<img width="1720" height="356" alt="image" src="https://github.com/user-attachments/assets/46d2c509-0766-4ab3-9c23-45b188e51345" />

Open Terminal and run:

```bash
mkdir -p ~/ps5_wallpapers
cd ~/ps5_wallpapers

wget https://github.com/MasterPS0/Linux-desktop-wallpapers-for-PS5/releases/download/v1.0/Linux.desktop.wallpapers.for.PS5.zip

unzip Linux.desktop.wallpapers.for.PS5.zip

sudo cp -r ./* /usr/share/backgrounds/

sudo chmod -R 755 /usr/share/backgrounds/
