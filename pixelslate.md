# Linux

## version check

```
$ cat /etc/issue
Debian GNU/Linux 9 \n \l

$ cat /etc/os-release
PRETTY_NAME="Debian GNU/Linux 9 (stretch)"
NAME="Debian GNU/Linux"
VERSION_ID="9"
VERSION="9 (stretch)"
VERSION_CODENAME=stretch
ID=debian
HOME_URL="https://www.debian.org/"
SUPPORT_URL="https://www.debian.org/support"
BUG_REPORT_URL="https://bugs.debian.org/"

$ hostnamectl
   Static hostname: penguin
         Icon name: computer-container
           Chassis: container
        Machine ID: 749f18d84c9643ed98915e2895e6d81a
           Boot ID: 67168f028de9418593cd7111c06de145
    Virtualization: lxc
  Operating System: Debian GNU/Linux 9 (stretch)
            Kernel: Linux 4.19.79-07511-ge32b3719f26b
      Architecture: x86-64
      
```
https://linuxize.com/post/how-to-check-your-debian-version/

## update
> $ sudo apt-get update && sudo apt-get dist-upgrade

https://support.google.com/pixelslate/answer/9136958?hl=en
