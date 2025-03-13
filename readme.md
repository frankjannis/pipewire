https://gitlab.freedesktop.org/pipewire/pipewire/-/wikis/Virtual-Devices

Place configs into

`~/.config/pipewire/pipewire.conf.d/`


Restart pipewire:

`systemctl --user restart pipewire.service`


List ouput or inputs:

`pw-link -o`
`pw-link -i`
