# altcz
AltGr-based keyboard layout for Czech diacritics.

# Installation

1. Paste the contents of `altcz` to the end of `/usr/share/X11/xkb/symbols/cz`

    ```bash
    cat cz altcz > cz
    ```

2. Add definition from `evdev.xml` to the Czech section in `/usr/share/X11/xkb/rules/evdev.xml`.
