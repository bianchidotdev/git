# bianchidotdev's Private Git Server

A personal ssh git server running Charm's [soft-serve](https://github.com/charmbracelet/soft-serve) git server.

Currently locked down to just me. No read access until I figure out how secure and reliable it is.

## NOTE

With fly.io, it seems that allocating a dedicated ipv4 IP address is required to get the persistent TCP connection to work.
Unfortunately, that took a number of hours to figure out.
