# CnC_Remastered_Collection
More Quality of Life Improvements

A simple mod that adds more quality-of-life improvements to the game. Does not add extra units or direct gameplay changes, so you get the true original experience, just improved. Currently includes the following enhancements:

Smarter Harvesters
Several enhancements have been added to make harvesters smarter.

In the original game, harvesters preferred harvesting ore patches to the north of their position. This mod makes them harvest the ore patches closest to their last refinery instead, which helps keep your harvesters safe and keeps the money flowing faster as the harvesters have a shorter path to home.

If you have multiple bases or a very large base, harvesters will now stick to using the closest refineries instead of wandering all around the map to reach any free refinery.

Harvesters also don't start idling anymore if their refinery gets destroyed while they are on their way to unload, but will instead find another refinery to unload to.

And finally, when the map runs out of ore, the harvesters won't stay idle permanently, but will periodically scan if more ore has spawned on the map (from ore mines). This also affects the Skirmish AI and makes it a bit less braindead in the late-game.

Pathfinding
Improves pathfinding by implementing the A* algorithm. Units will no longer hug cliffs and other obstacles, but move through the most optimal path. Special thanks to cfehunter for implementing this feature to TD, which I could then port to RA.

Factory rally points
You can select a factory and then click on the ground to give produced units a rally point, like in Red Alert 2 and CnCNet Tiberian Sun. This works with barracks, war factories and naval yards / sub pens. You can also hold ALT while giving the rally point to set the rally point to a unit or other object. Thanks to cfehunter for his work on the same feature for TD.

Other enhancements
Aircraft can be targeted manually with SAM sites and AA guns, making it possible to micro them for focus-fire
Enables force-fire (CTRL) for buildings
Enables the Stop (default S) command for buildings, so you can stop them from firing at a previously given target
Units react faster to enemies that move by their position
Service Depots now always tell fully repaired units to move out of the depot to keep it free for future use, even if there was no unit queued for entering them
Enables units to make queued waypoint loops if you make a path with Q-move and finally click on the unit itself (thanks to dkeeton for providing information about this)
