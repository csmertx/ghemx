# ghemx
ghem: A Klingon [word](http://klingonska.org/dict/?q=ghem)  for midnight snack

![Screenshot](screenshot.png)

## Dependencies
- bash
- libnotify (Ubuntu: libnotify-bin)
- kdialog (KDE Desktop)
- mplayer (notification sounds)
- dunst (tiling WMs)
- mutt (email notifications)
- gpg key to [encrypt](https://pthree.org/2012/01/07/encrypted-mutt-imap-smtp-passwords/) .muttrc (if [mutt](https://wiki.archlinux.org/index.php/Mutt))

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
-x            Save timer (e.g. -x 'seitan' -m 10)
              (becomes current title)
-z            Restore timer (e.g. -z 'tendies')
-t            Timer title (defaults to: ????)
-r            Timer hours
-m            Timer minutes
-s            Timer seconds
-a            Send alert email (e.g. -t 'example' -s 15 -a y)
</pre>
