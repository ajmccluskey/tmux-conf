tmux-conf
=========

Tmux configuration and layouts.

* rebind prefix to `C-a`, which is really easy to reach when you map Caps to be a Ctl key
* bind pane movement and resizing to use Vim movements (hjkl keys) so you can stay in the home position
	+ `C-a [hjkl]` switches pane left, down, up, right respectively
	+ `C-a Shift + [hjkl]` resizes pane in the direction left, down, up, right respectively
* bind `C-a` to move to your last window, so you can quickly switch between two windows by holding Ctl and
  double tapping a, which is equivalent to `C-a C-a`, or prefix + C-a

To install, just copy or link tmux.conf to ~/.tmux.conf and you should be good to go.
