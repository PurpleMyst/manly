# manly
manly is a compliment to man pages.

It's a lot like [explainshell](https://explainshell.com)
(don't worry, that is explain-shell, not explains-hell).

Your good friend has a funky alias in [his dotfiles](
https://github.com/8Banana/dotfiles/blob/master/__Myst__/.zshrc):
`alias alert="notify-send -i terminal -t 5 'Alert from Terminal!'"`:

```
$ manly notify-send -it

notify-send - a program to send desktop notifications
=====================================================

      -t, --expire-time=TIME
              The duration, in milliseconds, for the notification to  appear  on  screen.
              (Ubuntu's Notify OSD and GNOME Shell both ignore this parameter.)

      -i, --icon=ICON[,ICON...]
              Specifies an icon filename or stock icon to display.

```

Short and sweet!


## Installation
manly supports Python 2 and 3

    $ pip install manly


An unofficial Arch User Repository is maintained by mpolidori at
https://aur.archlinux.org/packages/manly/.


## Develop with me :)

Ideas, contributions and everything else is welcome!

``` bash
$ git clone https://github.com/carlbordum/manly
$ cd manly
$ python -m venv manlyenv
$ . manlyenv/bin/activate
$ python manly.py
```

Make sure test locally before sending a Pull Request using:

``` bash
$ pip install pytest
$ py.test
```
