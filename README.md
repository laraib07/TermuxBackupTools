# Rewind - A termux backup/restore tool


Introducing rewind - the ultimate solution for all your data backup and restore needs on the popular Android terminal emulator, Termux. Say goodbye to the hassle of manual data transfer and hello to seamless backups with just a few simple commands. With rewind, you can easily backup your important files, and even better, create a list of all the packages you've installed so they can be reinstalled with ease during a restore. Experience the power and convenience of rewind, the ultimate backup and restore tool for Termux.

![rewind](rewind.png)


### created by [Laraib07](https://github.com/laraib07)

## Installation

Just copy paste this in your termux.


```bash
wget https://raw.githubusercontent.com/laraib07/TermuxBackupTools/master/rewind && chmod u+x rewind && mv rewind $PREFIX/bin/
```

or

```bash
curl -O https://raw.githubusercontent.com/laraib07/TermuxBackupTools/master/rewind && chmod u+x rewind && mv rewind $PREFIX/bin/
```

## Usage

Usage : **rewind**  [-hv] [-b|-r [home|pkgs]]

option           |   Description
:---------------:|:---------------------------:
 -h              |    print this usage
 -v              |    print version
 -b [home\|pkgs] |    backup home and/or packages
 -r [home\|pkgs] |    restore home and/or packages

