Jitsi Meet
----------

Flatpak wrapper around the official Jitsi Meet desktop application - https://github.com/jitsi/jitsi-meet-electron

## Wayland support

Some of Jitsi Meet's features like screensharing aren't guaranteed to work under Wayland.

Wayland support can be disabled by setting `--nosocket=wayland` either using [Flatseal](https://flathub.org/apps/details/com.github.tchx84.Flatseal), or the command line, like so:

```
$ flatpak override --user --nosocket=wayland org.jitsi.jitsi-meet
```

Wayland support can also be temporarily enabled for a single run:

```
$ flatpak run --nosocket=wayland org.jitsi.jitsi-meet
```
