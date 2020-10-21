Celeste D-sides Randomizer
==========================

This is a collection of randomizer configuration files and routing descriptions for the [D-sides pack](https://gamebanana.com/maps/202524) of maps for [Celeste](http://www.celestegame.com/). 

The config is designed to be compatible with the [Celeste Randomizer](https://github.com/rhelmot/CelesteRandomizer).

**Note**: For the best experience, it is recommended to play the D-sides first before playing the randomizer add-on.


Installation
------------
**Note**: Running mods with Celeste requires you to have installed [Everest](https://everestapi.github.io/).

1. Download the [D-sides pack](https://gamebanana.com/maps/202524).
2. Download the [Celeste Randomizer](https://gamebanana.com/tools/6848).
3. The config is included by default within the D-sides pack, and the D-sides will be available in the randomizer level select screen.

![level select](docs/img/level_select.PNG)


Difficulty Modes
----------------

The difficulty modes are intended as follows:

- *Normal:* Easier D-side rooms, requires only common speedrun tech (neutrals, super/hyper/wavedashes, reverses)
- *Hard:* Average D-side difficulty, may require tech taught in the D-sides (bubble hypers, cassette jumps, etc.)
- *Expert:* Harder D-side rooms, may require some setupless moves (corner jumps, easy demodashes, etc.)
- *Perfect:* Hardest D-side rooms, may require multiple setupless moves and/or obscure tech (e.g. updiag demos)

These are loosely based off the original randomizer difficulty recommendations but are *not* equivalent. A good rule of thumb is that Normal and Hard are a level higher than their vanilla counterparts, and they start evening out in Expert. Perfect is probably easier than in the main game due to removing pixel-perfect demos and other frustrating moves. The reason for this difficulty organization was due to the low number of difficulty categories vs. the wide range of difficulty represented in the D-sides. If another difficulty category is added to the randomizer, the difficulties may be updated to match the vanilla randomizer more closely.

The ratings are based on difficulty of execution and assume that you have played the D-sides before. If you haven't, some screens may be harder than the ratings imply.

If you find new routes or would like to suggest tweaks or changes to difficulty ratings, feel free to contact me! You can see the current difficulty ratings in the [documentation](docs/routing).


Known Issues / Planned Additions
--------------------------------
1. There are not a huge number of dashless screens, which means you may have to supplement from the base game/other mods to generate larger/interesting dashless maps.
2. Camera work needs to be done for most reverse paths -- the routes with the worst camera were focused on for now. If you run across a route with a bad camera that significantly affects gameplay, let me know.
3. Currently most non-exits/entrances are disabled for now, which means the "Strange Holes" setting doesn't have a strong effect. I'll gradually add some strange holes in on a case-by-case basis, since turning them all on at once tends to break things.
4. My skill level has definitely changed throughout labbing this, so some of my difficulty ratings may not be entirely consistent!
5. A few 3D rooms may have some odd entrances/exits that are a half-tile off -- this is done to avoid softlocks due to how the roof decals are implemented.
6. I will make the config compatible with new randomizer features as they are created (e.g. clutter flag/lightning routing is currently being worked).


Contact
-------

If you encounter any issues/softlocks or have suggestions, you can reach me on Discord (Bigkahuna#0491). You can also ping me in the #randomizer channel in the main [Celeste Discord](https://discord.gg/g8Mw3XH). To minimize issues, use the latest version of the config and the randomizer mod. Please include randomizer version, seed, and settings in any bug reports.


Credits
-------

**Creator**: Bigkahuna

**Labber-in-Chief**: [Theta](https://www.twitch.tv/thetagc)

**D-sides Creator**: [Monika](https://www.twitch.tv/monika523)

**Randomizer Support**:
* Rhelmot
* Marlin

**Playtesters**:
* Etpio5
* Mnstrman06