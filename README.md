# Backporting Terminator from Hirsute

This is a quick smash-and-grab of Hirsute packaging for Terminator 2.1.0, subsequently modified to work for Ubuntu Bionic.

## Building

1. Download Terminator 2.1.0 source
1. Install build dependencies (see `control` for current list)
1. `cd` into the source directory and clone this repo `git clone ... debian`
1. `debuild -us -uc`
