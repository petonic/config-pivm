# config-pivm
Overlay dotfiles for pivm host

Mostly, contains binaries for the PI VM Image that get overlaid into ~/bin.

## Usage

To install these files on a VM, do the following:

```
cd ~
git clone git@github.com:petonic/config-pivm.git
cd config-pivm
cp -vr . ~       # Overlay them on our home directory
```
