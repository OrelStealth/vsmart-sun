# Simple smartprop for making env_sun cheap analogue

# How to install and use it:

  1. Download the latest version from [release page](https://github.com/OrelStealth/vsmart-sun/releases)
  2. Put files to "game/csgo_addons/map_name" folder
  3. Find "sun" smartprop in asset browser and place it into skybox map, preferably to "0 0 0" coordinates.
  4. Copy "Angles" from light_environment and paste them to the "sun" smartprop angles
  5. Set "Skybox scale" in parameters depending on sky_camera scale settings. The higher skybox scale the better since it will be available to put sun planes further.
  6. Set other parameters such as tint, glow, scale and distance.


# Can't see sun or sun flickers:

If sun planes don't show up in hammer, it still might render in-game, but it's a signal, that it's better to lower sun distance or use higher skybox scale. Skybox scale 1 allows to set sun disk distance only up to ~50000 units to make it look without glitches, which may cause sun looks like it moves.

# Sun disk materials example:
![sun1](https://github.com/user-attachments/assets/ac1c8de8-1162-4783-86b1-8551f58bbbf7)


# Glow example:
![sun2](https://github.com/user-attachments/assets/0b248c04-f855-463a-b1b4-19b1812b0c94)
