# acos
Arcade live iso for 
https://github.com/gravity-nerds/acmenu

## What is this?
Run an Arch Linux live iso to run the acmenu for my school's arcade

It has full drivers for Intel and AMD GPU drivers

can launch any Linux games (within reason) and has basic wine support

## Install + Requirements
Need https://gitlab.archlinux.org/archlinux/archiso and archlinux (pacman at least)

    sudo pacman -S archiso
    git clone https://github.com/gravity-nerds/acos && cd acos
    cd airootfs && git clone https://github.com/gravity-nerds/acmenu
    cd .. && sudo mkdir /tmp/work && sudo mkarchiso -v -w /tmp/work/ -o acos/out/ acos/
wait for your PC to melt, it might spit out an iso named `arog_linux-DATE.iso`

Then flash the iso onto a USB using https://etcher.balena.io/

## Known issues
Audio maybe? I can't test that in a vm
## Untested features
RN it works in a VM
The rest is untested

## If something goes wrong
Discord balaro4242
Or if Discord doesn't work... Instagram https://www.instagram.com/balaro4242/ (don't kill me for this)
