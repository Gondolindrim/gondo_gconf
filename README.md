# Gondolindrim's Gnome Terminal profile configurations
This is my Gnome Terminal profile configuration settings (yes, I am that vanilla).

The configuration revolves around a Solarized Dark color palette with modifications for a higher contrast. The font used is also reduced for information density and code readability.

## How to use

Download `gnome-terminal-profiles.dconf` and run

`dconf load /org/gnome/terminal/legacy/profiles:/ < gnome-terminal-profiles.dconf`

If you want to export a new `.dconf` file with your modifications, use

`dconf dump /org/gnome/terminal/legacy/profiles:/ > gnome-terminal-profiles.dconf`
