![build](https://img.shields.io/badge/build-pass-greenlight) ![status](https://img.shields.io/badge/status-tested-greenlight) ![flavor](https://img.shields.io/badge/flavor-regular-blue) ![tag](https://img.shields.io/badge/tag-1.9.3.0-blue)

# yocto-pitrezor
OS linux platform for the pitrezor project (usign yocto)

This code is used to build the linux platform image for the raspberry pi zero to be able to run the pitrezor software at bootup.

## How to build pitrezor image? 

1. [Install Docker](https://docs.docker.com/engine/installation/)
2. `git clone https://github.com/mvietri/yocto-pitrezor.git`
3. `cd yocto-pitrezor`
4. `sudo ./build-pitrezor.sh TAG` (where TAG is 1.9.3.0 for example, if left blank the script builds latest commit in this branch)

This creates file `build/pitrezor-TAG.zip`.

## Builds

Date: Sat, 05 Sep 2020 13:00:00 GMT

Name: pitrezor-1.9.3.0.zip

Size: 10815325 bytes (10 MiB)

SHA256: 0F5E5E5B3A79E56965601C5225DC61FC7249A95245C3137BE78D8D8D2CFDEF61

## Donate

Donate [Heneault](https://github.com/heneault) for his amazing work. More info at [pitrezor](http://www.pitrezor.com) page. 

I also will provide pi0 image as soon as a new firmware is available. [My bitcoin address](https://www.blockchain.com/btc/address/3Kfg5WP6uSWoxyDDkmGeY2V9qtT44F9TuC).


