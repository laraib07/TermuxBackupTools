# Rewind - A termux backup/restore tool


Simple bash script to backup and
restore home directory and packages installed manually.

![rewind](rewind.png)


### created by [Laraib07](https://github.com/laraib07)

## Installation

Just copy paste this in your termux.

1.

```bash
apt-get update && apt-get upgrade -y
```

2.

```bash
apt-get install wget curl tar -y
```

3.

```bash
wget https://raw.githubusercontent.com/laraib07/TermuxBackupTools/master/rewind && chmod u+x rewind && mv rewind $PREFIX/bin/
```

or

```bash
curl -O https://raw.githubusercontent.com/laraib07/TermuxBackupTools/master/rewind && chmod u+x rewind && mv rewind $PREFIX/bin/
```

## Usage

Usage : **rewind**  [-hvb] [-r home|pkgs]

option |   Description
:-----:|:---------------------------:
 -h    |    print this usage
 -v    |    print version
 -b    |    backup home and packages
 -r    |    restore home or packages
 
