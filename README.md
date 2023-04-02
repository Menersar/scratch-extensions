# scratch-extensions

# Instructions 

## How I created this repository

1. Create new folder (e. g. `scratch-extensions`) and `cd` into it.
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

3. Link and install the repos.
```shell
yarn install ../scratch-gui/
```
```shell
yarn unlink
```
```shell
yarn link ../scratch-gui/
```
```shell
cd ..
```
```shell
cd scratch-desktop
```
```shell
yarn add scratch-gui
```
```shell
cd ..
```
```shell
cd scratch-vm
```
```shell
yarn unlink
```
```shell
yarn link
```
```shell
cd ..
```
```shell
cd scratch-desktop
```
```shell
yarn add scratch-vm
```
```shell
yarn install
```
