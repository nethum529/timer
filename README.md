# timer

A minimal countdown for the terminal. One file, no dependencies.

```
timer           # type a time, then press enter
timer 25        # 25 minutes
timer 90s
timer 1h30m
timer 1:30      # 1 minute 30 seconds
```

## Controls

| Input | Action |
| --- | --- |
| Type digits | Set a time, like a microwave: 130 is 1:30 |
| Enter, space | Start or pause |
| Click the time | Type a new time |
| Scroll on the time | Change hours, minutes or seconds |
| +0:30, +1:00 | Add time |
| r | Reset |
| esc | Cancel typing, or quit |
| q | Quit |

## Install

Needs Python 3.8 or newer, and a terminal that draws octant block
characters (kitty, ghostty, foot, wezterm).

```
curl -fsSL https://raw.githubusercontent.com/nethum529/timer/main/timer -o ~/.local/bin/timer
chmod +x ~/.local/bin/timer
```

## License

MIT
