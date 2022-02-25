# Screen commands

#### Good to know commands
```
screen -S <name>  # Create session with new name
Ctrl+a d	# detach screen from terminal	Start screen with -r option to reattach
Ctrl+a A	# set window title	 
Ctrl+a x	# lock session	Enter user password to unlock
Ctrl+a [	# enter scrollback/copy mode	Enter to start and end copy region. Ctrl+a ] to leave this mode
Ctrl+a ]	# paste buffer	Supports pasting between windows
Ctrl+a >	# write paste buffer to file	useful for copying between screens
Ctrl+a <	# read paste buffer from file	useful for pasting between screens
```

#### create/navigate/delete windows with in screen session
```
Ctrl+a c	# new window	 
Ctrl+a n	# next window
Ctrl+a p	# previous window
Ctrl+a "	# select window from list
```

#### Split screen vertical/horizantal/navigate
```
Ctrl+a S or :split	       # split terminal horizontally into regions
Ctrl+a | or :split -v	     # split terminal vertically into regions
Ctrl+a :resize             # resize region	 
Ctrl+a :fit	               # fit screen size to new terminal size
Ctrl+a :remove             # remove region
Ctrl+a tab                 # Move to next region	 
```

