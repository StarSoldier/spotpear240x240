# spotpear240x240
Spotpear 1.54" joypad key binding and screen resolution (Raspberry OS) config.txt
My config file for using Spotpear 1.54" 240x240 screen with 480x480 resolution and buttons mapped and ready to use.


Joystick button press = Enter
Up/Down/left/Right
Start = Ctrl
Select = Alt
A = Shift
X = X
B = Backspace
Y = Delete
Right shoulderbutton = META/Win
Left shoulderbutton = Esc


Copy/paste this at the very end of config.txt (located in either /boot/config.txt) or /boot/firmware/config.txt
Keycodes can be swapped to any keypress/command

dtoverlay=gpio-key,gpio=3,active_low=1,gpio_pull=up,keycode=28
dtoverlay=gpio-key,gpio=5,active_low=1,gpio_pull=up,keycode=103
dtoverlay=gpio-key,gpio=6,active_low=1,gpio_pull=up,keycode=106
dtoverlay=gpio-key,gpio=16,active_low=1,gpio_pull=up,keycode=108
dtoverlay=gpio-key,gpio=13,active_low=1,gpio_pull=up,keycode=105
dtoverlay=gpio-key,gpio=26,active_low=1,gpio_pull=up,keycode=56
dtoverlay=gpio-key,gpio=19,active_low=1,gpio_pull=up,keycode=29
dtoverlay=gpio-key,gpio=21,active_low=1,gpio_pull=up,keycode=54
dtoverlay=gpio-key,gpio=20,active_low=1,gpio_pull=up,keycode=14
dtoverlay=gpio-key,gpio=15,active_low=1,gpio_pull=up,keycode=45
dtoverlay=gpio-key,gpio=12,active_low=1,gpio_pull=up,keycode=111
dtoverlay=gpio-key,gpio=14,active_low=1,gpio_pull=up,keycode=125
dtoverlay=gpio-key,gpio=23,active_low=1,gpio_pull=up,keycode=1
