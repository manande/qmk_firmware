# Manande's GMMK Pro config

These are some very basic settings and rules for the GMMK Pro.

This config makes use of the very handy [rgb_matrix_map.h from gourdo1's config](https://github.com/qmk/qmk_firmware/blob/master/keyboards/gmmk/pro/rev1/iso/keymaps/gourdo1/rgb_matrix_map.h) (which is in turn based on Jonavin's work, see the file in this config for attributions).

# Features

* basic settings:
    * n-key rollover active
    * polling / debounce settings: 1 / 5
* RGB settings:
    * RGB timeout after 1 minute of inactivity
    * RGB off when USB is suspended
    * red capslock indicator (capslock key LED and top and bottom LEDs of left and right LED strip turn red)
* additional rotary encoder modifiers:
    * Fn-Modifier:
        * counter-clockwise: previous track
        * clockwise: next track
        * press: play / pause
    * shift:
        * counter-clockwise: page down
        * clockwise: page up