# m122-3270

![IBM Model M 122 key](https://i.imgur.com/Oo3Ozqz.jpg)

This is a replacement controller for the IBM Model M 122 key terminal keyboard running on a STM32F411 BlackPill, intended
to act as closely to the 3270 keyboard's functioning as possible while still being usable on a PC.

A schematic and Gerber files are publicly available for those wishing to have carrier boards made
professionally instead of handwiring things. The M122 matrix connectors plug right into it.

The JSON files may be uploaded into [EasyEDA](https://easyeda.com/) and modified there, and the modified boards ordered
directly from JLCPCB from the editor window.

The associated firmware is part of the QMK firmware package, found at https://github.com/qmk/qmk_firmware . It is in the 
[keyboards/tronguylabs directory](https://github.com/qmk/qmk_firmware/tree/master/keyboards/tronguylabs/m122_3270).
