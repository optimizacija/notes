# Polybar

Install polybar with yay:
```
yay -S polybar
```

Copy default config to *~/.config* folder:
```
cp /usr/share/doc/polybar/config ~/.config/polybar/config
```

## Bspwm Integration

Add these lines to *~/.config/bspwm/bspwmrc*.

``` zsh
# polybar
# kill previous instance(s)
killall -q polybar
# create a new instance
polybar palenight-bar &
```

TODO: work in progress
