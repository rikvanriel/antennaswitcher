# antennaswitcher
Software to configure and control a remote antenna switch

This software is written for a beaglebone board controlling relays
driving various antenna switches through its GPIO ports.

It is meant to include functionality to:
- Control multi-antenna, multi-radio switches, preventing multiple
  radios from being switched to the same antenna simultaneously.
- Present a web interface that is usable both from web browsers and
  radio programs.
- Have antenna information stored on the single board computer that
  drives the relays, and fed to software using the antenna switch
  over some sort of JSON/XML API.
- Contain security measures so particular systems can only switch
  the antenna port for their own connection, and not the antenna
  that the other radio is on.

Contributions to make it work on other systems (eg. Raspberry Pi)
besides beaglebone, or add other kinds of functionality, are welcome.

Rik van Riel
