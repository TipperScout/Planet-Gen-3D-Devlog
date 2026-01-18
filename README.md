# Planet-Gen-3D-Devlog
A devlog for my Scratch game Planet Gen 3D.
###### Link Back to Game: https://scratch.mit.edu/projects/1252872479/

The game first started being worked on on 12/6/25 at a bit after midnight.
Update log
~~~
12/7/25 - 2.0.0 
Launch
  -- Added the game (Temperature, spin, tilt, grass/water colors, clouds, map mode, terrain editing, save/load, planet name and rings).
~~~
~~~
12/7/25 - 2.0.1 
  -- Patched map UVs not aligning correctly
~~~
~~~
12/7/25 - 2.0.2
  -- Made it so clouds don't appear when cloud density is 0.
~~~
~~~
12/9/25 - 2.0.3
  -- Patched the smoothing bug at poles, and made the save list hide on start if shown.
~~~
~~~
12/9/25 - 2.0.4
  -- Made smoothing smooth in equirectangular space to allow for better sphere unwrapping.
~~~
~~~
12/10/25 - 2.0.5
  -- Made clouds smoother by not rounding their smoothing. Also patched the single cloud pixel randomly being in the bottom row above 0. Also also, made the equirectangular smoothing do more.
~~~
~~~
12/10/25 - 2.0.6
  -- Added planet OBJ exporting.
~~~
~~~
12/11/25 - 2.0.7
  -- Updated the sphere model for better UV unwrapping.
~~~
~~~
12/14/25 - 2.1.0
 -- Added Perlin noise! I used @cc386283's remix and a video by Acerola as a reference. Go check them out, they both make really cool things.
This also means that equirectangular smoothing was removed.
~~~
~~~
12/14/25 - 2.1.1
 -- Made the sliders based on the seed.
~~~
~~~
12/14/25 - 2.1.2
 -- Updated the number of octaves for the clouds, and made the planet have more differing terrain.
~~~
~~~
12/15/25 - 2.2.0
 -- Added prevailing winds, they are a bit laggy, but you can turn them off by setting cloud speed to 0.
~~~
~~~
12/19/25 - 2.2.1
 --  Made the skybox have a different resolution slider.
~~~
~~~
1/4/26 - 2.2.2
 --  Added planet size!
~~~
~~~
1/4/26 - 2.3.0
 --  Added an atmosphere!
~~~
~~~
1/5/26 - 2.3.1
 --  Added cities! Also added a toggle for lights in the general settings.
~~~
~~~
1/9/26 - 2.3.2
 --  Flipped the cloud brightness so that they start with the less dense clouds and move to the more dense. Also, made cities not appear in deserts, and that plants don't appear when not detecting water.
~~~
~~~
1/9/26 - 2.3.3
 --  Added a biome system, so now there are different plant colors for taiga and tropical, instead of it all being temperate.
~~~
~~~
1/9/26 - 2.3.4
 --  Made there be sand instead of plants when it gets too hot, so now there's sand in-between the rocks and the plants.
~~~
~~~
1/11/26 - 2.4.0
 --  Added more map modes, like height and heat. Also, now height and light effect the heat of water less.
~~~
~~~
1/11/26 - 2.4.1
 --  Made it so you can now click 'n drag to move camera, and scroll to zoom.
~~~
~~~
1/11/26 - 2.4.2
 --  Updated the sphere model again to make the exported OBJ planet have better lighting.
~~~
~~~
1/14/26 - 2.4.3
 -- Added music, credit:
    Composer: TipperScout
    Title: Celestial Dance
    Link: 
https://flat.io/score/69647b6039204453b5167e0c-celestial-dance
 -- You can now type R for the seed to get a random seed.
~~~
~~~
1/14/26 - 2.4.4
-- Patched map looping early bug
-- Made noise size smaller, so there's more continentalness to worlds before I add tectonics.
-- Increased frequency on city noise.
~~~
~~~
2.5.0 - 1/16/25
-- Add plate tectonics! This includes voronoi noise for the plates, and then tectonic activity for mountains and valleys.
-- Added a maps to see tectonic plates, and interactions. Blue is convergent, green divergent and red is transform. Though, transform boundaries don't do anything currently.
-- Lowered stone threshold for mountains from 50 to 25.
-- Renamed "Default" map to "Surface"
~~~
~~~
2.5.1 - 1/17/25
-- Made is so that plates moving in the same direction don't get assigned to transform boundaries, and work better based on the stored angles.
~~~
~~~
2.5.2 - 1/17/26
-- Transform faults now effect terrain!
-- Also made oceanic land lower at plate boundaries when converging with continental crust.
-- Also increased noise at coastlines
~~~
~~~
2.5.3 - 1/18/26
-- 
~~~
~~~
2.5.4 - 1/18/26
-- Updated shorelines so they raise terrain less.
~~~
