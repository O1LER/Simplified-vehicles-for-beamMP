# Simplified-vehicles-for-beamMP
Creating the missing simplified vehicles as a mod for beamNG, to be used in beamMP

Since beamNG is missing many simplified models for its vehicles, and because they can save a lot of processing power, they might be useful for multiplayer servers with a lot of players/cars or for players with a weak PC.


Please adhere to the internal names of beamNG vehicles, to make communication easier and prevent misunderstandings.
Please open a branch for each vehicle. Only PR to main if you are satisfied with your work and think that the vehicle is in a usable state.
This repo is public and the result of it will be:
A: published to the beamNG repo for anyone to use on their server (or singleplayer if they desire) as a beamNG mod
B: integrated into the beamMP mod, and thus distributed by the beamMP system
Please keep this in mind before starting to contribute.

For the moment, vehicles are split into these groups:

## First: Self-Supported Body
autobello, barstow, bastion, bolide, miramar, racetruck, rockbouncer, sbr, scintilla, wendover

These can be based on the existing simplified vehicles by beamNG

## Second: Body-on-Frame
burnside, bluebuck, fullsize, hopper, moonhawk, midtruck, pickup, pigeon, roamer, van, wigeon

They need an empty (no mesh/nodes/beams) frame part, that then has the body as a sub-part. Necessary to be able to use different bodys on the same frame part (mainly for pickup, van and roamer)
May be based on existing simplified vehicles by beamNG

## Third: Large vehicles
citybus, semi

May need a completely new node/beam structure

Priority should be given to the first group. Getting every vehicle into a usable state, with one single subpart per part option. We can always expand, for example the bumper selection, to the same variety that the full vehicles has at a later date.
