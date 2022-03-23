# Axet's Call Recorder

This module installs axet's [Call Recorder](https://f-droid.org/en/packages/com.github.axet.callrecorder/)
as a system app, allowing it to use the `CAPTURE_AUDIO_OUTPUT` system permission to properly record calls.

Minimum supported API is 19 (Android 4.4). This module is probably not needed on older Android versions anyway.


## Features

* Compatible with F-Droid updates: update the app to the latest version via F-Droid.
* Systemless: this module does not alter your system.


## How to use

* Download the [latest release](https://github.com/akaessens/callrecorder-axet/releases/latest/download/callrecorder-axet.zip) and install the module using Magisk.
* Reboot.
* Open Call Recorder, modify settings as desired (you might want to leave "Recording Source" on "Auto";
there's **NO** need to use root (for "System Mixer Incall Recording") in the app).
* Activate call recording by checking the "Calls Recording" checkmark.
* Enjoy!


## Links

Call Recorder by axet: [f-droid link](https://f-droid.org/en/packages/com.github.axet.callrecorder/),
[sources](https://gitlab.com/axet/android-call-recorder).


Magisk module repo: [akaessens](https://github.com/akaessens/callrecorder-axet) (original: [di72nn](https://github.com/di72nn/callrecorder-axet))


## License

[GNU GPLv3](LICENSE).
