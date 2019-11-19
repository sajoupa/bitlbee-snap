# bitlbee-snap

This is a snap for bitlbee, a gateway to many IM protocols for IRC.
More information: www.bitlbee.org

To build the snap, run `snapcraft` in this directory on Ubuntu 18.04 or later, and install with `sudo snap install bitlbee*.snap`

## Snap usage
`service snap.bitlbee-sajoupa.bitlbee` # copies the config file from the source if needed, and run bitlbee in ForkDaemon mode

## Config file
`$SNAP_DATA/bitlbee.conf`
