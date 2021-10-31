# ansible-raspberrypi-playbooks
These are playbooks I use in to manage raspberry pi and other single board computers.

They are being executed from a Raspberry Pi 4 running Ubuntu.

These have been tested against raspberry pis running several different OSs, the rock pi-s single board computer running debian based OSs, and LattePanda running Suse..

Example inventory is included and should be edited to manage your devices.

Group vars do not include passwords or vault information at this time.  Might update this later.

Combine some of the playbooks to get better results as necessary.
-For example update and restart required playbooks will notify you if any updates require a restart of a particular system.

