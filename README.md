# pranklock

[![CircleCI](https://circleci.com/gh/RealOrangeOne/pranklock.svg?style=svg)](https://circleci.com/gh/RealOrangeOne/pranklock)

Based on the original work of [@Adimote](https://github.com/adimote) in [this version](https://github.com/trickeydan/dotfiles-ubuntu/blob/master/files/desktop/i3/pranklock.sh).

Locks the screen with a screenshot of the desktop. If any key is pressed, or the mouse moves, capture an image with the webcam, and lock the screen again using that.

## Dependencies

- `i3lock`
- `ffmpeg`
- `xdotool`

## Usage

1. Install the above dependencies
2. Run the `pranklock` script to _lock_ your screen

By default, the first webcam (`/dev/video0`) is used. To change this, pass the video device as an argument (eg `pranklock /dev/video1`)

3. To safely unlock without showing the webcam image, press the Escape key. You can then unlock as normal.
