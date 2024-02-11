Hero TNT Mod
======================
See license.txt for license information.

Author of hero_tnt fork 
Neuromancer (MIT)

Authors of original tnt mod source code
----------------------
PilzAdam (MIT)
ShadowNinja (MIT)
sofar (sofar@foo-projects.org) (MIT)
Various Minetest developers and contributors (MIT)

Authors of media
----------------
BlockMen (CC BY-SA 3.0):
All textures not mentioned below.

ShadowNinja (CC BY-SA 3.0):
tnt_smoke.png

Wuzzy (CC BY-SA 3.0):
All gunpowder textures except tnt_gunpowder_inventory.png.

sofar (sofar@foo-projects.org) (CC BY-SA 3.0):
tnt_blast.png

paramat (CC BY-SA 3.0)
tnt_tnt_stick.png - Derived from a texture by benrob0329.

TumeniNodes (CC0 1.0)
tnt_explode.ogg
renamed, edited, and converted to .ogg from Explosion2.wav
by steveygos93 (CC0 1.0)
<https://freesound.org/s/80401/>

tnt_ignite.ogg
renamed, edited, and converted to .ogg from sparkler_fuse_nm.wav
by theneedle.tv (CC0 1.0)
<https://freesound.org/s/316682/>

tnt_gunpowder_burning.ogg
renamed, edited, and converted to .ogg from road flare ignite burns.wav
by frankelmedico (CC0 1.0)
<https://freesound.org/s/348767/>


Introduction
------------
This mod adds a special kind of TNT to Minetest that only destroys those nodes that can be destroyed in the game H.E.R.O. (for now just default:cobble).
This mod recreates the TNT mechanic of the game H.E.R.O.
hero_tnt is a fork of tnt mod in Minetest Game
The point of this mod is to be a part of a set of mods that recreate the game H.E.R.O. in Minetest.  (one of my favorite childhood games)  
To that end, one of the major changes is that this forked version of mod only destroys those nodes that can be destroyd in the game H.E.R.O. (for now just default:cobble).
H.E.R.O. gameplay can be seen here: https://www.youtube.com/watch?v=nD0VTuVQ6Tg
H.E.R.O. Player Manual: https://atariage.com/manual_html_page.p ... abelID=228
There will be a number of mods all beginning with "hero_" so that eventually if you enable all of them you will essentially be playing the game hero.
The plan is to have all of these "hero" mods function as stand alone mods so that they can combined in other ways with other mods to work with and create other games.


How to use the mod:

Craft gunpowder by placing coal and gravel in the crafting area.
The gunpowder can be used to craft TNT sticks or as a fuse trail for TNT.

To craft 2 TNT sticks:
G_G
GPG
G_G
G = gunpowder
P = paper
The sticks are not usable as an explosive.

Craft TNT from 9 TNT sticks.

There are different ways to ignite TNT:
  1. Hit it with a torch.
  2. Hit a gunpowder fuse trail that leads to TNT with a torch or
     flint-and-steel.
  3. Activate it with mesecons (fastest way).

For 1 TNT:
Node destruction radius is 3 nodes.
Player and object damage radius is 6 nodes.
