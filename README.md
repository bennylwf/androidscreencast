# androidscreencast
Automatically exported from code.google.com/p/androidscreencast
Desktop app to control an android device remotely using mouse and keyboard. Should work on Windows/Linux/MacOS with any android device.

I've created a google groups HERE for support, no direct help request please.

Installation
Install the android sdk (download here)
Connect your device through USB cable and ensure it's detected with "adb devices"
Make sure you have Java Runtime Environnement 5 or later installed
Click HERE. You can launch it by typing "javaws <jnlp file>" from a command line.
If mouse/keyboard control doesn't work, open a command line and type :

adb shell
su
chmod 777 /data/dalvik-cache
cd /data/dalvik-cache
chmod 777 ./
Features
Mouse and keyboard control FOR ROOTED DEVICES ONLY
Landscape mode (right click)
Video recording
Basic file browser
Current limitations
Slow refresh rate (about 4-5 fps)
Not all keycode are mapped. See KeyMapping
Todo
Automatic screen rotation based on the device current state.
Improve speed
Audio redirection
How can i help ?
Donate using this button :  (Thank Daniel and Tyler !)
Report issues, submit patch, ...
