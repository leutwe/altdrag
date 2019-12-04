
# Changes to https://github.com/stefansundin/altdrag

Scroll through the middle mouse key pressed and mouse moving. Only if key is pressed for more than 200ms this feature will be get active. If the key is pressed for a shorter time, normal functionality of the button will be done.

It is only enabled if "Scroll inactive windows" is enabled at General settings of AltDrag.

This is similar to xinput "Evdev Wheel Emulation" and "libinput Scroll Method Enabled" feature.


If you want to use this with a TrackPoint set at Mouse Properties "Middle Button Action" to "Use as middle click".
Additional I recommend setting the Wheel to the smallest possible value (1).


# Build

Build is done through ./build.bat x64 in a x64 cygwin enviroment with mingw gcc installed.
