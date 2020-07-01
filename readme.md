# fceux for PG2 v2

A fork of fceux for the Pocketgo2 v2 (New PocketGo v2) but should work on
the PG2 v1 and RG350 as well.


IMPORTANT NOTE: Be sure FPS throttling is turned off, the emulator may not
work properly properly when it is turned on.  Toggling fast forward on with
FPS throttling enabled is guaranteed not to work and will just cause sound
issues and slowdowns rather than speeding things up.  Unfortunately I have no 
idea how to fix it (I am not really a developer, I can compile stuff and make 
some minor edits like changing hotkeys but that is about it).


## Changes

Toggle fast forward hotkey changed from L to R2 and it actually works
(sorry, there is no way to change the fast forward speed at the moment)

Can bring up the menu via the menu button (SDLK_RCTRL) as well as L2 or the
power button.

Insert Coin is R + DOWN rather than R + LEFT.

### Hotkeys

Menu - Menu button on PG2 v2, power button, or L2
Fast Forward Toggle - R2
Save State to current slot - R + A
Load State from current slot - R + B - WARNING: state will be loaded with no confirmation
Toggle Fullscreen - R + X
Flip FDS Disk - R + Y
Toggle FPS Display - R + Up
Insert Coin - R + Down
Take Screenshot - R + Select
Pause Emulation - R + Start

####  Build notes

Use http://www.gcw-zero.com/files/opendingux-gcw0-toolchain.2014-08-20.tar.bz2
to build as newer buildroots/toolchains will have problems with unresolved
symbols resulting in an immediate crash back to the system menu.
