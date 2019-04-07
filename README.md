![One Dark preview][preview-img]

# Oceanic Next for GNOME Terminal

> Oceanic Next theme for GNOME Terminal

Here is [Oceanic Next][oceanic-next] theme for GNOME Terminal (available on Ubuntu, Fedora, Elementary OS, etc).

## Installation

For installation just execute desired command below. Be careful, terminal will be closed after install.

```
wget https://raw.githubusercontent.com/denysdovhan/oceanic-next-gnome-terminal/master/oceanic-next.bash && chmod +x oceanic-next.bash && ./oceanic-next.bash
```

If your terminal profile is not updated after executing the script you might be missing `dconf-tools`. On **Ubuntu** you can install them by executing:

```
sudo apt-get install dconf-tools
```

Executing the script again should now edit the profile correctly.

## Colors

This theme uses [color palette][palette] from original [Oceanic Next][oceanic-next] theme for Sublime Text 2/3:

![Palette][palette-preview]

## License

[MIT][mit-license] © [Denys Dovhan][denysdovhan]

[preview-img]: https://cloud.githubusercontent.com/assets/3459374/9465490/b92dfea8-4b35-11e5-81f5-0b8e421e9ddc.png
[oceanic-next]: https://github.com/voronianski/oceanic-next-color-scheme
[palette]: ./COLORS
[palette-preview]: https://raw.githubusercontent.com/voronianski/oceanic-next-theme/master/colors.png
[mit-license]: http://opensource.org/licenses/MIT
[denysdovhan]: http://denysdovhan.com/
