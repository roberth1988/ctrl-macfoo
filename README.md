# Massdrop Ctrl

This repository contains some layouts for my CTRL Keyboard from Massdrop.

I am mainly a Mac user and therefore the layouts are inspired by Mac Keyboards such as the Magic Keyboard 2 or the standard keyboard layout of my MacBooks.

## Massdrop Ctrl Configurator
I currently use the  Massdrop Web-based configurator to configure my layout.

*Layer 0*
![Keyboard Layer 0](https://raw.githubusercontent.com/roberth1988/ctrl-macfoo/master/images/ctrl_massdrop_mac_layer0.png)

*Layer 1*
![Keyboard Layer 1](https://raw.githubusercontent.com/roberth1988/ctrl-macfoo/master/images/ctrl_massdrop_mac_layer1.png)

## How to flash under Mac
The mdloader can be found on [GitHub - Massdrop/mdloader: Massdrop Firmware Loader (CTRL Keyboard)](https://github.com/Massdrop/mdloader)

1. Download  `mdloader_mac` and `applet-flash-samd51j18a.bin` and put them in the same folder.
2. Do then `chmod u+x mdloader_mac` to make it executable.
3. Put now your keyboard into reset mode
4. `mdloader_mac --first --download massdrop_ctrl_config_CTRL_Mac_MagicKeyboard.bin --restart`

Voila it should work now and the LED should be on again.

