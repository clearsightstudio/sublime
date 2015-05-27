# ClearSight Sublime Text 3 Preferences

## Installation Instructions

Close Sublime.

```sh-session
$ cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages
$ mv User OLD_User
$ git clone git@github.com:clearsightstudio/sublime.git User
$ cd User
$ git checkout -b <yourname>
```

Note: if you're not in the ClearSight organization, you'll need to do this on the third line:

```
$ git clone https://github.com/clearsightstudio/sublime.git User
```

Start Sublime. Package Control will install any new packages.

## Updating

```sh-session
$ cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User
$ git fetch origin master:master
$ git merge master
```

## Uninstalling

```sh-session
$ cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages
$ rm -rf User
$ mv OLD_User User
```

Restart Sublime.

### License

MIT license. Copyright 2015 Jamon Holmgren.
