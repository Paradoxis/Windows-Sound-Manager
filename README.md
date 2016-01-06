# Windows-Sound-Manager
Control your volume mixer on Windows with Python 3

## How it works
This script emulates keystrokes using the built in windows `VK_VOLUME_MUTE`, `VK_VOLUME_DOWN` and `VK_VOLUME_UP` keys, which are used to control the default audio settings.

## Why would I use this?
As I found out, changing your audio settings programmatically with programming language is incredibly tedious. It requires knowledge of tons of DLL's and tens to force you to change the sound on every single device at hardware level individually. By using a small hack that uses the built in media keys, you can avoid all of this by using something which was built into the OS already.

This isn't a fool-proof solution, but it works if you just need to build a quick application that requires your sound to to controlled with code.

## Specifications
* **Tested on:** Windows 10
* **Python version:** Python 3.5

## Links
* [Virtual-Key Code list](https://msdn.microsoft.com/en-us/library/windows/desktop/dd375731(v=vs.85).aspx)
* [C struct code](http://stackoverflow.com/questions/13564851/generate-keyboard-events)
* [C struct code credit](https://github.com/lucasg)
