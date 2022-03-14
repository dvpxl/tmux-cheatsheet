Work in Progress

TMUX CHEATSHEET

=========================
Trigger Prefix: CTRL + B 
Help: ?
Config File:  ~/.tmux.conf

Window and Splits
=========================
New Window:       C
Split Horizontal: "
Split Vertical:   %
Change to Window:  [0..9]
Next Window: N
Prev Window: P

Window Tiling Presets:
=========================
Space Horizontal:            Option + 1
Space Vertical:              Option + 2
Horizontal Main + Vertical:  Option + 3
Vertical Main + Horizontal:  Option + 4
Tile All:                    Option + 5

Window Pane Navigation:
=========================
Next: O (for other)
Arrow Navigation:  Up/Down/Left/Right 

Terminal: :
=========================
Synchronize: :setw synchronize-panes
Disable: <repeat same command>

Server:
=========================
tmux kill-server

