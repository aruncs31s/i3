## Change

### Rofi

- deleted

```
-kb-cancel Alt-F1 \

```

from the ~/.config/i3/scripts/rofi_launcher 


- key binding

```

## Set stacking layout
bindsym $MOD+Shift+z layout stacking, $send-notify 'Layout - Stacking'
## Set tabbed layout
bindsym $MOD+Shift+x layout tabbed, $send-notify 'Layout - Tabbed'
## Set default layout
bindsym $MOD+Shift+c layout default, $send-notify 'Layout - Default'
## Toggle between stacking/tabbed/split:
bindsym $MOD+Shift+v layout toggle, $send-notify 'Cycling Layouts'
## change container layout (stacked, tabbed, toggle split)
## Toggle between horizontal/vertical:
bindsym $MOD+Shift+b layout toggle split, $send-notify 'Layout - Hor/Vert'
## Toggle fullscreen
bindsym $MOD+f fullscreen toggle, $send-notify 'Toggled Fullscreen'
## Toggle floating/tiling
bindsym $MOD+space floating toggle, $send-notify 'Toggled Floating Mode'


## -- CLI Apps --
bindsym $mod+d				exec --no-startup-id $rofi_applets/rofi_launcher
bindsym $mod+n 			exec --no-startup-id "$alacritty -e nvim"
bindsym $mod+r 			exec --no-startup-id "$alacritty -e ranger"
# bindsym $ALT+Control+h 			exec --no-startup-id "$alacritty -e htop"

## Sets focus to the nearest container in the given direction.
bindsym $MOD+j focus left
bindsym $MOD+k focus down
bindsym $MOD+l focus up
bindsym $MOD+semicolon focus right


```
