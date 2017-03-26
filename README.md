# slk

[![Greenkeeper badge](https://badges.greenkeeper.io/passcod/slk.svg)](https://greenkeeper.io/)

_Slack wrapper for use as desktop app._

![Screenshot](https://i.imgur.com/D32V7Nb.png)

Uses [node-webkit] to provide a single-purpose window
onto Slack's web version.

Will not work with node-webkit < 0.10.

[node-webkit]: https://github.com/rogerwang/node-webkit
[release]: https://github.com/passcod/slk/releases

## running…

### …from source:

```bash
$ $package_manager install node-webkit
$ git clone git://github.com/passcod/slk.git
$ cd twd
$ nw .
```

### …from package:

- Install [node-webkit].
- Download latest [release].
- Run it.

### …on archlinux:

[AUR package](https://aur.archlinux.org/packages/slk)

```bash
$ yaourt -S slk
$ slk
```

A `.desktop` file (for graphical menus) is also provided.

## legal

Slack, SlackHQ, and the Slack logo are trademarks
of, and copyrighted to, SlackHQ, Inc.

All other files are released in the Public Domain as per
my [policy](https://passcod.name/PUBLIC.txt).
