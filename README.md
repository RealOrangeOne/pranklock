# pranklock

[![CircleCI](https://circleci.com/gh/RealOrangeOne/pranklock.svg?style=svg)](https://circleci.com/gh/RealOrangeOne/pranklock)

Based on the original work of [@Adimote](https://github.com/adimote) in [this version](https://github.com/trickeydan/dotfiles-ubuntu/blob/master/files/desktop/i3/pranklock.sh).

Locks the screen with a screenshot of the desktop. If any key is pressed, or the mouse moves, capture an image with the webcam, and lock the screen again using that.

## Dependencies

- `i3lock`
- `ffmpeg`
- `xdotool`

__Note__: This is currently untested on multi-monitor setups
