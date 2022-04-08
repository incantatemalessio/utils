# utils

ionic 6.19.0
Angular CLI: 7.3.9
Node: 14.17.3
npm 6.14.13
cordova 11.0.0
git version 2.30

//Install Node by NVM
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ] && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh" # This loads nvm
source ~/bashrc
nvm list-remote
nvm install v14.17.3
node -v

//Install NPM
sudo apt install npm
npm -v

//Install Cordova
npm install -g cordova


Buttercup
Android Studio
Anydesk
OBS


GlobalProtect
Teams
Thunderbird


//Install Global Protect
curl https://vpn.wisc.edu/clients/PanGPLinux-5.3.2-c3.tgz --output PanGPLinux-5.3.2-c3.tgz
tar -xvf PanGPLinux-5.3.2-c3.tgz
sudo dpkg -i GlobalProtect_deb-5.3.2.0-3.deb

//Open Global Protect
globalprotect
globalprotect connect --portal GPP.arcacontal.com

//Uninstall
sudo dpkg -P globalprotect
