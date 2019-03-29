# ghemx


[![asciicast](https://asciinema.org/a/202617.svg)](https://asciinema.org/a/202617)


<img src="https://github.com/csmertx/ghemx/blob/master/ghemx_screenshot.png?raw=true" alt="Preview of ghemx"/>

## Dependencies
- bash
- libnotify (optional)
- mutt (optional)
- gpg key to encrypt .muttrc (optional)

## Installation
- cp to /bin/ghemx(-cli) or: place wherever and add alias to .$SHELLrc
- First run installs a config file in ~/.config/ghemx
- Add i3blocks/timer_monitor to bar config if needed

## Usage
<pre>
ghemx is a distraction free timer for X
usage: ghemx [-ahlxztrms] [--help] [--list]
-h|--help     Read me
-l|--list     List directory of ghemx tmp & save files
              and list saved timer entries
-x            Save timer (e.g. -x 'Waffles' -m 12)
              (becomes current title)
-z            Restore timer (e.g. -z 'example')
-t            Timer title (default: Timer)
-r            Timer hours
-m            Timer minutes
-s            Timer seconds
-a            Send alert email (e.g. -t 'example' -s 15 -a y)
</pre>
