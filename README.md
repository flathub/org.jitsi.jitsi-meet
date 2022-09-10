Jitsi Meet
----------

Flatpak wrapper around the official Jitsi Meet desktop application - https://github.com/jitsi/jitsi-meet-electron

## Wayland support

Jitsi Meet's Wayland support is currently experimental, and some features like screensharing are broken.

Wayland support can be enabled by setting the environment variable `JITSI_USE_WAYLAND=1` either using [Flatseal](https://flathub.org/apps/details/com.github.tchx84.Flatseal), or the command line, like so:

```
$ flatpak override --user --env=JITSI_USE_WAYLAND=1 org.jitsi.jitsi-meet
```

Wayland support can also be temporarily enabled for a single run::

```
$ flatpak run --env=JITSI_USE_WAYLAND=1 org.jitsi.jitsi-meet
```
