# Mouse configuration with xbindkeys

This is my mouse configuration using `xbindkeys`.

The mouse I am using is `Mad Catz R.A.T.5`

# Files

* `.xbindkeysrc` is the configuration file. It holds the rules, which are then loaded from `xbindkeys`

* `update.sh` is simple bash script, which copies the config file to `~/.xbindkeysrc` and reloads the program.
  You can run it using.
  ```
  ./update.sh
  ```

* `README.md` is the file you are reading at the moment

# Dependencies

To use this you need to install:

* `xbindkeys` - the program, that listens for keyboard commands
```
sudo apt-get install xbindkeys
```

* `xvkbd` - a program, that simulates key presses. (you can press keyboard keys using commands)
```
sudo apt-get install xvkbd
```

* `xinput` **OPTIONAL** - I am using this to identify which keys are which on my mouse.
```
sudo apt-get install xinput
```

# My shortcuts

* move workspace up/down with the horizontal scroll
* move window workspace up/down with Ctrl+horizontal scroll
* refresh browser pages (or hit `F5`) with the aim button
