# scratch-extensions

# Instructions 

## How I created this repository

1. Create new folder (e. g. `scratch-extensions`) and change into the directory.
```shell
mkdir scratch-extensions
```
```shell
cd scratch-extensions
```

2. Download and extract repositories into the new folder. <br />
https://github.com/Menersar/scratch-desktop
https://github.com/Menersar/scratch-gui
https://github.com/Menersar/scratch-vm
```shell
git clone https://github.com/Menersar/scratch-desktop
```
```shell
https://github.com/Menersar/scratch-gui
```
```shell
https://github.com/Menersar/scratch-vm
```

## Create a project build

1. Change into directory `scratch-desktop`.
```shell
cd scratch-desktop
```

2. Install dependencies.
```shell
yarn install
```

3.Create a project build.
```shell
yarn build
```

# Sources

Packaging electron apps with OS-specific bundles via JS or CLI:
https://github.com/electron/electron-packager

Scratch 3.0 as a self-contained desktop application:
https://github.com/LLK/scratch-desktop

Graphical User Interface for creating and running Scratch 3.0 projects:
https://github.com/LLK/scratch-gui

Virtual Machine used to represent, run, and maintain the state of programs for Scratch 3.0:
https://github.com/LLK/scratch-vm

Scratch-gui wiki:
https://github.com/LLK/scratch-gui/wiki/Getting-Started

Extension development:
https://medium.com/@hiroyuki.osaki/how-to-develop-your-own-block-for-scratch-3-0-1b5892026421

Examples of GPIO Scratch extensions:
https://github.com/MrYsLab/s3onegpio

Packaging an Electron app for Raspberry Pi
https://stackoverflow.com/questions/57518370/packaging-an-electron-app-for-raspberry-pi-3

Debian package for your Electron app for Raspberry with a Debian OS:
https://github.com/electron-userland/electron-installer-debian