Jitsi Meet
----------

Flatpak wrapper around the official Jitsi Meet desktop application - https://github.com/jitsi/jitsi-meet-electron

## Wayland support

Screensharing works under Wayland, and uses the OS chooser instead of the Jitsi internal one.

Wayland support can be disabled by setting `--nosocket=wayland` either using [Flatseal](https://flathub.org/apps/details/com.github.tchx84.Flatseal), or the command line, like so:

```
$ flatpak override --user --nosocket=wayland org.jitsi.jitsi-meet
```
