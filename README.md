termux install xfce debian proot

```bash
pkg update
pkg install x11-repo
pkg install termux-x11-nightly
pkg install proot-distro
proot-distro install debian
proot-distro login debian
apt update -y
apt install nano adduser
apt install sudo
adduser root
nano /etc/sudoers
su ~ root
whoami
sudo whoami
sudo apt install xfce4 -y
```
