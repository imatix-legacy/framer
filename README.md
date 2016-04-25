# Framer

`framer` is a companion to `libero` from iMatix Corporation, which
generates a Framed HTML view (hence the name) of the `libero` dialog
(state machine description).

It is written in Perl v4, and implemented using a state machine, for 
which the implementation (in `framer.d`) is built using `libero` to 
process the state machine source (in `framer.l`); `framer.fmt` was 
written by hand to support the various `framer` actions referenced
by the state machine.

Brief documentation is available in [framer.man](framer.man); apart from
this the only documentation is the source code.

`framer.zip` contains the original release artefact (the only release
every made stand alone); the other files were unpacked from `framer.zip`
for ease of reference.

Released under the GNU GPL v2, a copy of which can be found in 
[COPYING](COPYING).
