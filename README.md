# Rewind
---
![rewind](https://raw.githubusercontent.com/laraib07/TermuxBackupTools/master/rewind.png)

Simple bash script to backup and
restore termux(an android terminal emulator).

###created by [Laraib07](https://github.com/laraib07)

##Installation
---
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
wget https://raw.githubusercontent.com/laraib07/TermuxBackupTools/master/rewind && chmod u+x rewind && mv rewind /data/data/com.termux/files/usr/bin/
```

or

```bash
curl -O https://raw.githubusercontent.com/laraib07/TermuxBackupTools/master/rewind && chmod u+x rewind && mv rewind /data/data/com.termux/files/usr/bin/
```

## Usage
---
Usage : **rewind**  [option]

option |  long-option  | output
:-----:|:-----------:|:---------------------------:
  -h   |  --help      |    print this usage and exit
  -v   |  --version   |    print version
  -b   |  --backup    |    take termux backup
  -r   |  --restore   |    restore texmux
 
