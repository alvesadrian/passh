`passhmenu` is a [dmenu][]-based interface originally made for [passh][], the standard Unix password manager. This design allows you to quickly copy a password to the clipboard without having to open up a terminal window if you don't already have one open. If `--type` is specified, the password is typed using [xdotool][] instead of copied to the clipboard.

# Installing

    cd passh/contrib/dmenu
    sudo make install

# Uninstalling
    
    cd passh/contrib/dmenu
    sudo make unistall

# Usage

    passhmenu [--type] [dmenu arguments...]

Using your desktop tools, a keyboard binding can be created to launch it when pressing certain keys, which makes it very usefull.

[dmenu]: http://tools.suckless.org/dmenu/
[xdotool]: http://www.semicomplete.com/projects/xdotool/
[passh]: https://passh.hackan.net/
