# Black Hole Virtual Audio Driver V0.1

## Description
    Black Hole is a modern MacOS virtual audio driver that allows applications to pass audio to other applications.

## Installation Instructions
    1. Build driver
    2. Copy BlackHole.driver to "/Library⁩/Audio⁩/Plug-Ins⁩/HAL"
    3. Restart computer or use terminal command "sudo killall coreaudiod"

## Customization
    In "BlackHole.h" change "NUMBER_OF_CHANNELS" to the desired number of channels.