# ShellView

Summary   | Current Release
----------|-----------------------
Version   | 1.0
Date      | November 17, 2021
Platforms | macOS, Linux (Ubuntu+), Windows
Author    | Abe Pralle

# About
ShellView is a console-based image viewer. It uses character block graphics and ANSI colors to display JPEGs, PNGs, and BMPs. Useful in environments without a graphical user interface or in order to take a quick look at images from the command prompt.

# Demo
![Demo](Media/Videos/ShellView-Demo.gif)

# Reference Images
Gauntlet II | Minmei                                       | Sunflowers
------------|----------------------------------------------|-----------
![Gauntlet II](Media/Thumbnails/GauntletII.jpeg) | ![Minmei](Media/Thumbnails/Minmei.jpeg) | ![Sunflowers](Media/Thumbnails/Sunflowers.jpeg)

# Installation

## Morlock Install (Recommended)
1. Install [https://morlock.sh](morlock.sh)
2. `morlock install abepralle/shellview`

## Manual Install
1. Install [https://github.com/AbePralle/Rogue](Rogue) and [https://github.com/AbePralle/Rogo](Rogo).
2. Clone this repo and run `rogo install`.

# Usage
    USAGE
      shellview [OPTIONS] [image-filepaths...]

    COMMANDS (INTERACTIVE MODE)
      I, O, LEFT/RIGHT CLICK, SCROLL WHEEL
        Zoom in or out.

      WASD, HJKL, ARROW KEYS, MOUSE DRAG
        Scroll around image if zoomed in.
        Cycle next/previous image if zoomed out (A/D, H/L, LEFT/RIGHT).

      N, B or C, Z
        Cycle to (N)ext image or (B)ack to previous image.
        Alternately, (C)ontinue to next or (Z)=back.

      R
        Toggle color dithe(R)ing.

      Q, ESCAPE
        Quit ShellView.

    OPTIONS
      --dither, -d
        Start with color dithering turned on (toggle with R).

      --help, -h, -?
        Show this help text.

      --print, -p
        Print all images to the console (scaled to fit) without entering interactive mode.

