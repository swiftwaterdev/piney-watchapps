# piney-watchapps

https://github.com/JF002/Pinetime/commit/50ae0ae5e073ac48652e6c26549f9b19655e8da3

I'm very happy to publish this new version of InfiniTime because it contains new features and bugfixes that have been mostly implemented by contributors to the project, not by me !

This version introduces the first 2 games into InfiniTime. The first one is the Paddle game from ZephyLabs, a single player pong game. The second one a 2048 clone from jedmijares.

The time needed to turn the display on when pushing on the button has been improved, and the small glitch that displayed the time it was when the display was shut down has been removed, thanks to IoTPanic.

A first step to the internationalization of the firmware has been taken by AirHamster who added the support for notifications written in Cyrillic.

The docker image (and the associated documentation) has been greatly improved by pfeerick and Nuxij.

Regarding the code quality, okaestne did a nice job by cleaning all the #includes of the project, and fixed some build issues and warnings at the same time.

Finally, the bug that would display an erroneous battery level in the app SystemInfo has been fixed by IoTPanic.