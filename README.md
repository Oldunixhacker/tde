# TDE

A desktop enviornment built using the Tk toolkit.

## Dependencies

Python and the tkinter module.

## Install

### Package

Not yet.

### Manual install

```
wget https://raw.githubusercontent.com/TylerMS887/tde/stable/install.sh
chmod +x install.sh
```

When downloaded, run with:

```
bash install.sh
```

## Launching

In an X11 display manager, select the "TDE" session.

TDE is not compatible with Wayland, and will likely never will be, because Tk
is old and only supports the older X11 standard.

It's planned to add Wayland support by adding an XWayland session for TDE.
