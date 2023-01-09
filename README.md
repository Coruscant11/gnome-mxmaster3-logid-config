# gnome-mxmaster3-logid-config
My [Logiops](https://github.com/PixlOne/logiops) configuration file for the MX Master 3 on Gnome 40+. \
Enabling mouse gestures.

## Installation

### Download software

```sh
sudo apt install cmake libevdev-dev libudev-dev libconfig++-dev
git clone https://github.com/PixlOne/logiops.git
cd logiops
mkdir build
cd build
cmake ..
make
```

### Write configuration file

Save [logid.cfg](logid.cfg) in `/etc/logid.cfg`
