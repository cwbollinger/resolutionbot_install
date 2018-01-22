# resolutionbot_install Instructions
```
cd ~/resolutionbot_ws/src
git clone git@github.com:cwbollinger/resolutionbot_install.git
# make a softlink to the rosinstall file
ln -s resolutionbot_install/.rosinstall
# Install using wstool
wstool update
# install javascript dependencies for extended_teleop
cd prg_woz/extended_teleop
npm install
```
