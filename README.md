# Exodus-Wallet-Updater
A linux updater for the Exodus.com crypto wallet 

I built this because for some reason the devs dont put this simple feature in the linux deb. This is built on 18.04LTS but should run on any variant of debian. 
Currently tested and working on 20.04
Suggestions are welcome


How it works - 
This script will always check for the latest version for the exodus wallet. Please follow the on screen instuctions. The script will also check my git repo for any updates. So if anything brakes the script like the recent domain chnage for exodus.io to exodus.com. Once i put the chnage in place your script will pick it up and update auto matically. Follow the onscreen prompts. 
The script downloads the latest .deb file from the website. Checks hashes against there hosted database to make sure no tampering with the file. Installs it and then runs.

How to setup - 
Open Terminal and type:

git clone https://github.com/DatLinuxGuy/Exodus-Wallet-Updater.git 
chmod +x Exodus-Wallet-Updater/exodus-update
./Exodus-Wallet-Updater/exodus-update

To update exodus simply open a terminal and type - 
exodus-update 
