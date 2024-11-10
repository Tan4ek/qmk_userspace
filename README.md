# QMK Userspace 

## Howto to build firmware for Aurora Lily58

1. Enable (make sure) userspace in QMK config using `qmk config user.overlay_dir="$(realpath qmk_userspace)"`
2. Run `qmk compile -e CONVERT_TO=liatris -kb splitkb/aurora/lily58 -km tan4ek-Lyli58`

## How to run application to display custom data on OLEDs

Install and run [qmk-display](https://github.com/Tan4ek/qmk-display)
