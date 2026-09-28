# timer

A minimal countdown for the terminal. Big numbers, mouse control, one file, no dependencies.

```
timer 25        # 25 minutes
timer 90s
timer 1h30m
timer 1:30      # 1 minute 30 seconds
timer           # start at 00:00 and scroll to set
```

## Controls

| Input | Action |
| --- | --- |
| Click, space | Start or pause |
| Scroll on a number | Change that number |
| Right click, r | Reset |
| Up, down | Change minutes |
| q, esc | Quit |

## Install

Needs Python 3.8 or newer.

```
curl -fsSL https://raw.githubusercontent.com/nethum529/timer/main/timer -o ~/.local/bin/timer
chmod +x ~/.local/bin/timer
```

## License

MIT
