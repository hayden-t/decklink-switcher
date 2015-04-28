This lets you switch decklink inputs from the command line.

This is modified source from/for the DeviceList sample in the Black Magic Designs Decklink SDK

Currently coded for Decklink Mini Recorder, though may work with other models or could be coded too.

haydent
www.httech.com.au
```
Usage: DeviceList.exe <device> <option>

Where <option> is one of:

list            -       Print Connections Available
get             -       Get current connection state
sdi             -       Switch to SDI Input (and save)
hdmi            -       Switch to HDMI Input (and save)


attr            -       Print Device Attributes
out             -       Print Device Output Modes
in              -       Print Device Input Modes
```

discussion:
http://forum.blackmagicdesign.com/viewtopic.php?f=18&t=35031
http://casparcg.com/forum/viewtopic.php?f=12&t=3144