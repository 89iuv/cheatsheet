# Tmux CheatSheet

## Windows
ctrl+b - c
	new window

ctrl+b - ,
	rename window 

ctrl+b - <number>
	switch to number window

ctrl+b - p
	previous window

ctrl+b - n
	next window

ctrl+b - &
	close window	

## Panes
ctrl+b - arrows
	travel between panes

ctrl+b - %
	split vertical

ctrl+b - " 
	split horizontal

ctrl+b - hold(alt) + arrows
	resize pane

ctrl+b - z
	zoom into pane

## Sessions
ctrl+b - d
	disconnect tmux 

ctrl+b - $
	rename session

ctrl+b - s
	sessions overview

## Application
tmux attach
	attach to tmux

tmux attach -t <name>
	attach to session <name>

tmux list-sessions
	list tmux sessions

tmux kill-server
	kill all tmx sessions
