# NumPad

NumPad is a custom keyboard layout

## Layout

![NumPad layout](./NumPad-layout.png?raw=true)
> Layout generated with [Keyboard layout editor](http://www.keyboard-layout-editor.com)

## Building guide

### Step 1 : Print plate
Plate schema is available [here](./plate/) in different format ([SVG](./plate/NumPad.svg), [EPS](./plate/NumPad.eps) or [DXF](./plate/NumPad.dxf))
> Plate files generated with [kb_builder](https://github.com/swill/kb_builder)

### Step 2 : Make case
Todo

### Step 3 : Soldering components
Todo

### Step 4 : Install firmware
I created a layout with [QMK_Firmware](https://github.com/qmk/qmk_firmware) for this keyboard.
#### Step 4.1 Compile from sources
[Clone this repo](https://github.com/Dolu89/qmk_firmware)
```
cd SRC_QMK/keyboards/dolu_numpad
make default
```
Get hex file generated in .build folder
#### Step 4.1 Download HEX file
You can also download directly compiled HEX file [here](./firmware/dolu_numpad_default.hex)

