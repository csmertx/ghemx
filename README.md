# ghemx?
ghem - Klingon for midnight snack

## Dependencies
- bash
- libnotify (Ubuntu: libnotify-bin)
- kdialog (KDE Desktop)
- mplayer (notification sounds)
- dunst (tiling WMs)
- mutt (email notifications)
- gpg key to encrypt .muttrc (if mutt)

## Installation
- cp to /usr/bin/ghemx(-cli) or: place wherever & add alias to .$SHELLrc
- Add i3blocks/timer_monitor to bar config if desired

## Usage
- Run with your favorite launcher (Gnome 3: ALT+F2, dmenu, rofi, etc.)
- Tested with Gnome 3, KDE Desktop, i3wm, & bspwm, etc.
- First saved timer creates dir ~/.config/ghemx & ghemx_timers.conf if not found

<pre>
ghemx is a distraction fueled timer with notifications
usage: ghemx [-ahlxztrms] [--help] [--list]
-h|--help     Read me
-l|--list     List directory of ghemx tmp & save files
              and list saved timer entries
-x            Save timer (e.g. -x 'Waffles' -m 12)
              (becomes current title)
-z            Restore timer (e.g. -z 'example')
-t            Timer title (defaults to: ????)
-r            Timer hours
-m            Timer minutes
-s            Timer seconds
-a            Send alert email (e.g. -t 'example' -s 15 -a y)
</pre>
