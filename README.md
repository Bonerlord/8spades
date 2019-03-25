# 8 Of Spades

An early in-development fork of [Openspades](https://github.com/yvt/openspades) for /v/, to bring the game closer to the 0.52 trench warfare experience.

## What's the plan?

To implement client-side gameplay changes into the 8spades client, and server-side changes into a modified 0.75 8spades server.

As of writing the 8spades client is still compatible with a regular 0.75 server, although you'll find yourself at a disadvantage unless all players are using the 8spades client.

Once work on the server code begins, the client and server should both use a unique 8spades game version, to prevent mixing between 0.75 and 8spades clients.


## What's different?
### Current changes:
* Sprinting has been removed
* Autoclimb has been removed
* Movement slowdown when looking downwards has been removed
### Planned changes for v1:
* Intel capture reveals enemies on map for 60 seconds, like older versions
* Balanced weapon damage
* Increased grenade block damage
* Improved player spawns
* Server weapon restrictions
* Server fog radius control
* Server persistent map damage between rounds
* More features still under discussion

## How to build?
The same as [building Openspades](https://github.com/yvt/openspades/wiki/Building) for now. If that changes this page will be updated.

## Can I help?
Sure: Give suggestions, report bugs, or make merge requests.

## This is dumb
No u
