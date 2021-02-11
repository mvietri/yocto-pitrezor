![build](https://img.shields.io/badge/build-passing-greenlight) ![status](https://img.shields.io/badge/status-tested-blue) ![tag](https://img.shields.io/badge/tag-1.9.4.0-blueviolet) ![tag](https://img.shields.io/badge/tag-1.9.4.0--btc-yellow)

# yocto-pitrezor
OS linux platform for the pitrezor project (usign yocto)

This code is used to build the linux platform image for the raspberry pi zero to be able to run the pitrezor software at bootup.

## How to build pitrezor image? 

1. [Install Docker](https://docs.docker.com/engine/installation/)
2. `git clone https://github.com/mvietri/yocto-pitrezor.git`
3. `cd yocto-pitrezor`
4. `sudo ./build-pitrezor.sh TAG` (where TAG is 1.9.4.0 for example, or 1.9.4.0-btc for the bitcoin-only build, if left blank the script builds latest (regular fw) commit in this branch)

This creates file `build/pitrezor-TAG.zip`.

## Builds

Get latest and previous builds.

See [Github releases](https://github.com/mvietri/yocto-pitrezor/releases) page for more information.

## Donate

Donate [Heneault](https://github.com/heneault) for his amazing work. More info at [pitrezor](http://www.pitrezor.com) page. 

I also will provide pi0 image as soon as a new firmware is available. [My bitcoin address](https://www.blockchain.com/btc/address/bc1qmt8fnyjq96a79nvjjjphpq75933nj0mkrhxj93).

