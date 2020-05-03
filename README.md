# Rewind - A termux backup tool

![rewind](https://raw.githubusercontent.com/laraib07/TermuxBackupTools/master/rewind.png)

Simple bash script to backup and
restore termux(an android terminal emulator).

**caution :** Restoring of $PREFIX (i.e usr) is 
quite complicated. It has binaries that are 
architecture specific. It means same executable on 
aarch64 and armeabi-v7a will be different.
To avoid breaking termux , make sure
* you keep backup up-to-date.
* restore backup on same architecture.


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

Usage : **rewind**  [option]

option |  long-option  | Description
:-----:|:-----------:|:---------------------------:
  -h   |  --help      |    print this usage and exit
  -v   |  --version   |    print version
  -b   |  --backup    |    take termux backup
  -r   |  --restore   |    restore texmux
 
