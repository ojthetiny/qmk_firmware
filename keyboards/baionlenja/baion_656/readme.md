# Baion 656

WKL 65% PCB

* Keyboard Maintainer: [ojthetiny](http://ojdesigns.xyz) and on [GitHub](https://github.com/ojthetiny)
* Hardware Supported: Baion656 PCB with STM32F072
* Hardware Availability: https://baionlenja.com 

![Render](https://imgur.com/a/xcoTztv)

## Instructions

### Build

Make example for this keyboard (after setting up your build environment):

    make baion_656:default

Flashing example for this keyboard:

    make baion_656:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

### Reset

- Unplug
- Hold Escape
- Plug In
- Unplug
- Release Escape

### Flash

- Unplug
- Hold Escape
- Plug In
- Flash using QMK Toolbox or CLI (`make baion_656:<keymap>:flash`)
