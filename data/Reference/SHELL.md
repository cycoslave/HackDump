## stable shell using python
(Note that if the shell dies, any input in your own terminal will not be visible (as a result of having disabled terminal echo). To fix this, type reset and press enter.)
python -c 'import pty;pty.spawn("/bin/bash")'
export TERM=xterm
CTRL-Z
stty raw -echo; fg

## using rlwrap
rlwrap nc -lvnp <port>
CTRL-Z
stty raw -echo; fg
