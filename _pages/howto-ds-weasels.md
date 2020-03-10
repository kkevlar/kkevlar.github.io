---
permalink: /howto/ds-weasels/
title: "How to Play DS Games using Four Weasels"
excerpt: "Very fun"
redirect_from:
  - "/howto/ds-weasels.html"
  - "/howto/ds-weasels"
---

## Weasels

Weasels (aka Joy Cons) are a super easy way to transform any bad single player game into a multiplayer, cooperative experience.

<p align="center">
  <img src="https://www.defygaminguk.com/wp-content/uploads/2019/06/default-shell-600x408.png" alt="weasels" width="400"/>
</p>

## Motivation


<p align="center">
  <img src="/images/howto-ds-weasels-corey.png" alt="corey" width="450"/>
</p>

Ever wanted to play garbage, old DS games with your friends?
This method works best with games that mostly use the D-Pad / Buttons not touchscreen.
**Takes at most 5 mins.**


<p align="center">
  <img src="/images/howto-ds-weasels-jc-and-dir.png" alt="motivation" width="600"/>
</p>

This guide will show you how to set up four weasels to cooperatively control a retro DS game.


# Requirements

* Windows :( 
* 4 Charged "Weasels"
* Legally Aquired DS Rom

# Steps

1. Test your game w/ dessmume
2. Pair the weasels
3. Configure JoyToKey 
4. Fix DS hotkeys and controls

## Test your game w/ DeSmuMe 

Download [desume](http://desmume.org/download/) and try it on you ROM.

I'd recommend using both screens side by side:

![sbs](https://i.imgur.com/3YTMafC.png)

## Pair the Weasels

Connect weasels the same way you connect literally any bluetooth device.

![Bluetooth](/images/howto-ds-weasels-bluetooth-begin.png)

All four weasels should have "Connected" under them (not pictured here).

![All Paired](https://i.imgur.com/P7hqxPY.png)

## Configure JoyToKey 

Download the tool [here](https://kkevlar.github.io/files/JoyToKey_en.zip) or by visiting their [downloads page](https://joytokey.net/en/download)

First, make sure that all four weasels seem to visible by JoyToKey by clicking the "Options" tab.
![hi](https://i.imgur.com/PvEFg4B.png)

Next, open up the configuation folder.
![hi](https://i.imgur.com/iDZi4fk.png)

Copy [corey.cfg](/files/corey.cfg) into that folder.

You might need to restart JoyToKey with File->Exit to see they "corey" configuration show up on the left side.
Notice that **all** directions on controller 1 are bound to "W" (Up).
![hi](https://i.imgur.com/BQn2P9a.png)


## Fix DS Hotkeys and Controls

Have the Emulator show you what inputs are being pressed (for Troubleshooting):

![input](https://i.imgur.com/WNgTS8f.png)


Open the Controls Menu from the Emulation tab and change the controls to what you see in the image here:

![Control Menu](https://i.imgur.com/RDqyFEL.png)

Open the Hotkey menu and delete all of the hotkeys in the right column using escape.

![Hotkey Menu](https://i.imgur.com/o4ozMxG.png)

# Troubleshooting

## Weasels Keep Disconnecting

Move them closer.


