Backlight Control
=================

A simple backlight (brightness) control script.

To set a minimum brightness, change the line ``min_brightness = 0``.

Usage (i.e.)
------------

Increase:

    sudo ./backlight +10

Decrease:

    sudo ./backlight -10

As the script writes to a */sys* file, it needs to have root privileges. As you probably want to add the execution of the script to a keybinding (for example in your window manager configuration), you should consider adding the *NOPASSWD* option for that script to your sudoers.
