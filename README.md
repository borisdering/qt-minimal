# Basic WebEngine View With QML And Qt

## Using Own Yocto Qt SDK 
Source your SDK
```
$ . /opt/poky/3.1.10/environment-setup-cortexa7t2hf-neon-vfpv4-poky-linux-gnueabi
```
Generate Make file with QMake
```
$ qmake -makefile -o Makefile
```
Build your target
```
$ make
```