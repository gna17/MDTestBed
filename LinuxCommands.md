pwd :___ show absolute path

$git log -L :MainActivity:A1news/app/src/main/java/com/example/a1news/MainActivity.java :___ show git history of class MainActivity

$echo "cd ~/mnt/c/Users/Pesan/OneDrive/My_Project" >> ~/.bashrc : set default path

$sudo usermod -d /mnt/c/Users/Pesan/OneDrive/My_Project lynn : set user default directory, must log out first

change home directory:
$sudo nano /etc/passwd
change this line:
lynn:x:1000:1000:"",,,:/mnt/c/Users/Pesan/OneDrive/My_Project:/bin/bash

exit vim editor:
:q (withoutwriteout) :wq(withsaving)

upgrade to wsl 2 ubantu, see this:exit

https://docs.microsoft.com/en-us/windows/wsl/install-win10#step-2---check-requirements-for-running-wsl-2

$alias npp="/mnt/c/Program\ Files/Notepad++/notepad++.exe"   : set Notepad++ as default text editor, example: $npp text1.txt


1. Set up your git configuration with name and SFU ID.

$git config --global user.name "lynnShi"
$git config --global user.email "shuos@sfu.ca"
