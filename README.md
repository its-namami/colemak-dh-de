# Installation

To install this, use this command:

```bash
sudo install -Dm644 ~/.config/xkb/symbols/custom/usr/share/X11/xkb/symbols/custom
```

# Add to niri

At config.kdl, at input:keyboard:xkb, add/replace these lines:

```kdl
layout "custom"
variant "colemak_dh_de"
```

