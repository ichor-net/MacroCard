# MacroCard

*Guide coming soon!*


## Setup
So far only software setup is available and no hardware guide has been written. Software setup guide is linked here: [Guide](https://github.com/ichor-net/MacroCard/blob/main/MacroCard%20User%20Guide.pdf)


### QMK Default Information [ignore]
* Keyboard Maintainer: [ichor-net](https://github.com/ichor-net)
* Hardware Supported: ~~*The PCBs, controllers supported*~~
* Hardware Availability: ~~*Links to where you can find this hardware*~~

Make example for this keyboard (after setting up your build environment):

    make ichornet/macrocard:default

Flashing example for this keyboard:

    make ichornet/macrocard:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:
***Orientation is as follows:** **Top/North** is the encoder, **Right/East** is the type-c connector*

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (**0,0 is at the north-east key in the matrix**) and plug in the keyboard
* **Physical reset button**: With the two small buttons that are flush with the case at the top: press and hold top-most button (bootsel), press the bottom button (reset) once, then release the bootsel button once the device has shown up as a drive in your system.
* ~~**Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available~~
