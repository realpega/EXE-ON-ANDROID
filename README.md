#HOW TO RUN .EXE FILES ON ANDROID WITH GUI DESKTOP VIA TERMUX


apt update

apt install wget

wget https://raw.githubusercontent.com/realpega/termux-prefix-switcher/main/tps

bash tps switch

pkg update

apt install wget

apt install openssl-tool

apt install proot

hash -r

wget https://raw.githubusercontent.com/EXALAB/AnLinux-Resources/master/Scripts/Installer/Ubuntu/ubuntu.sh

bash ubuntu.sh

./start-ubuntu.sh

apt update && apt upgrade

apt install curl

curl -L -o de-apt-xfce4.sh https://raw.githubusercontent.com/EXALAB/AnLinux-Resources/master/Scripts/DesktopEnvironment/Apt/Xfce4/de-apt-xfce4.sh

bash de-apt-xfce4.sh

apt update && apt upgrade

apt purge libfprint-2-2:armhf

apt purge fprintd

apt purge libpam-fprintd:armhf

apt update && apt upgrade

cd .vnc

apt install sudo

sudo vncserver

apt install nano

nano xstartup

#!/bin/sh
unset SESSION_MANAGER
unset DBUS_SESSION_BUS_ADDRESS startxfce4 &
[ -x /etc/vnc/xstartup ] && exec /etc/vnc/xstartup
[ -r $HOME/.Xresources ] && xrdb $HOME/.Xresources
xsetroot -solid grey
vncconfig -iconic &

sudo vncserver -kill :1

exit

exit

./start-ubuntu.sh

sudo vncserver

startxfce4

apt update && apt upgrade

apt install neofetch

adduser

nano /etc/sudoers

ALL=(ALL:ALL) ALL

su

cd

sudo apt update && sudo apt upgrade

exit

apt install git

apt install wget

apt install curl

apt install tar

apt install gzip

apt install bzip2

apt install python

apt install python2

apt install python3

apt install cmake

apt install build-essential

apt install gcc-arm-linux-gnueabihf

sudo apt update && sudo apt upgrade

git clone https://github.com/ptitSeb/box86

cd box86

mkdir build

cd build

cmake .. -DARM_DYNAREC=ON -DCMAKE_BUILD_TYPE=RelWithDebInfo

make

cd

wget https://bit.ly/3mS4XeJ --no-check-certificate

tar zxvf 3mS4XeJ

rm 3mS4XeJ

wget https://7-zip.org/a/7z1900.exe --no-check-certificate

/root/box86/build/box86 /root/wine/bin/wine /root/7z1900.exe

/root/box86/build/box86 /root/wine/bin/wine /root/.wine/drive_c/7-Zip/7zFM.exe
