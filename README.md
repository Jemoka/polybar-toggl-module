# Polybar Toggl Module
A Toggl module for polybar. That's about it.

# Installation
You probably need to install the darn thing to use it, so here's how.

## TogglCli
This module requires `togglCli`, a Python toggl interface.

So, do yourself a favor and open your terminal emulator. Type

```bash
python -m pip install togglCli
```

Which will, of course, install togglCli.

Then, type

```bash
python -m toggl now
```

and toggl's cli will tell you a bit of setup stuff by requiring you to log into your toggl account.

Once `python -m toggl now` returns your current timer, you are good to go.

## Polybar Module
In `togglModule.ini`, there exists the module that you need to put into your `config` file for Polybar. That config file is usually in `~/.config/polybar/config`.

Also, you probably want to add the `toggl` module to one of your bars in one of the `modules-{left|center|right}` arrays.

Then, add `toggl.sh` to your polybar config directory as well (for the short of memory, put it in `~/.config/polybar/[here]`). That allows the Polybar module to talk to Toggl.

An example config (mine) is also included for funzies.

Enjoy!



@jemoka

