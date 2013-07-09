keyboard-maestro-macros
=======================

One repository for my Keyboard Maestro macros

It seemed like a waste to create a separate repo for each macro, when most of them just need a few lines of explanation and a link to the actual macro (which is just XML).

So I decided to put them all here (except for the ones which already have their own repo).

This README will (read: "should") have information about each macro.

## Disclaimer:
Use at your own risk. Read the comments. Feel free to ask questions if there's something you don't understand.

# Index of available macros

* [Keyboard Maestro Updates Keyboard Maestro](Keyboard-Maestro-Updates-Keyboard-Maestro.kmmacros) -- ([Raw Link](https://github.com/tjluoma/keyboard-maestro-macros/raw/master/Keyboard-Maestro-Updates-Keyboard-Maestro.kmmacros)): They said it couldn't be done… Ok, well, technically they just advised against it, but I did it anyway! I made a Keyboard Maestro macro which updates Keyboard Maestro itself.
	+ Every day at 3:00 a.m. (or via menu bar menu)
	+ Launch Keyboard Maestro.app
	+ Select "Check for Updates..."
	+ Wait for one of three things to happen:
		1. No update is available (button = "OK")
		2. Network connection failed (button = "OK")
		3. Update available (button = "Install Update")
	+ The macro will select either of those buttons. If there an an update, it will install and Keyboard Maestro will re-launch. We don't even need to do anything else.
* Next?

