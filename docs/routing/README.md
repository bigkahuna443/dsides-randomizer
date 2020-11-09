Routing
=======
These tables contain the routing information for every chapter of the D-Sides. There are also comments for some levels that have trickier solutions, or explanations on rating choices, cut routes, etc. If you would like to contribute to labbing or make suggestions, read the info below and then contact me with your findings (contact info [here](../../README.md#contact))!


Notation
--------
* D: dashes
* F: forwards
* R: reverse
* N/A: not possible
* P: power / lightning flag is set (i.e. turned off)
* T: towels flag is set
* B: books flag is set
* C: crates / boxes flag is set
* X': flag X is not set

e.g. "2DR" -> 2-dash reverse
e.g. "Expert, N/A (T)" -> default Expert, not possible with towels flag set


Room Tweaks
-----------
My goal with the randomizer was to make the minimum number of changes possible to make routes possible (e.g. opening up jumpthrus so you can backtrack). If an alternate route requires a change to be made that significantly affects the gameplay of the normal route, it likely will not be added. The one exception is that all inventory change triggers and "no refill" triggers have been removed to avoid changing the dash settings the player selects in the randomizer (this is done in the vanilla randomizer as well).


Known Missing Routes
--------------------
Here is a list of routes that are known to be possible but have not been completed RTA (i.e. without savestates or assist tools), which is a requirement to be included in randomizer:

* Any route that requires a pixel-perfect demo or ceiling pop and is otherwise impossible
* 3D:a-02 (TBC and T'BC) 2DR
* 3D:d-07 1DR/2DR
* 6D:boss-17 0DF
* 9D:m-06 1DR/2DR

If you beat any of these routes RTA, **send me a clip** and it will be added to the config.


Reverse Routes
--------------
Some screens are technically possible to complete in reverse, but were not included for one reason or another. I've included the most common reasons below so you don't waste time labbing these screens unecessarily:

1. Screen isn't interesting (e.g. fall straight down) / camerawork too complex / bad spawn options. These are the main subjective reasons for cutting rooms, all of which will be in comments for that room in the routing tables.
2. Rooms with a Badeline Boss or where a Badeline Orb launches you to the next screen are not possible in reverse due to how they are coded.
3. Rooms with a Theo gate at the end are not possible in reverse.
4. Rooms with multiple checkpoints (e.g. Summit flags) need to be forwards-only to avoid softlocks.


Flags
-----
To test rooms with different combinations of flags (e.g. lightning, clutter flags), you will need to set these flags in the debug console:

1. Go to a room that is not the starting room of the chapter.
2. Press the ` key on your keyboard.
3. Enter "flag [flag_name]" to set the flag, and "flag [flag_name] false" to unset the flag.
  a. oshiro_clutter_cleared_0: towels flag
  b. oshiro_clutter_cleared_1: books flag
  c. oshiro_clutter_cleared_2: crates/boxes flag
  d. disable_lightning: power/lightning flag
    * You can also use "ltng" and "ltng false" to set/unset this flag
4. Retry the room.


