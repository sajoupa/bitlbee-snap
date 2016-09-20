# bitlbee-snap

This is a snap for bitlbee, a gateway to many IM protocols for IRC.
More information: www.bitlbee.org

To build the snap, run `snapcraft` in this directory on Ubuntu 16.04 or later, and install with `sudo snap install bitlbee*.snap`

## Snap usage
`bitlbee` # generate a config file from the source template if needed, and run bitlbee in ForkDaemon mode
`bitlbee.bitlbee-stop` # stops bitlbee. It is a good idea to add `alias bitlbee-stop=bitlbee.bitlbee-stop` to your .bashrc or equivalent

## Config file
`$SNAP_USER_DATA/bitlbee.conf`

Each user on a system can run his own bitlbee, provided that they choose different ports. 
They can do so by editing their `$SNAP_USER_DATA/bitlbee.conf` .
