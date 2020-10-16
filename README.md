# BizHawk-Shuffler
A script and setup program to randomize games being played in BizHawk! Currently, players can slip ROMs into the CurrentROMs folder and have the play order generated by a Lua script. The setup program generates a seed, sets the min/max times of each game played before switching, and an option to include a countdown.

This version works specifically with a developmental build of BizHawk. Future official releases should also work with it. Confirmed version that works: https://gitlab.com/TASVideos/BizHawk/-/pipelines/203194311

Should be simple to get working! To use the shuffler, do the following:

1. Put ROMs into a "CurrentROMs" folder located in the same folder as SoloShuffler.lua. You may leave ROMs in a .zip, but do not leave them in a folder.
2. Run RaceShufflerSetup.exe to set your seed, your min/max time, and whether or not you want an on-screen three-second countdown for the upcoming swap.
2. Open Bizhawk.
3. Open a ROM for each console (NES, SNES, etc.) you're using, and map controls for them.
4. Go to Tools > Lua, then load the SoloShuffler.lua script.
5. Enjoy!

If you wish to change the min/max times, add/remove games during playthrough, add a countdown on the screen, and randomize the seed (recommended), open the RaceShufflerSetup.exe.

The file "CurrentROM.txt" will automatically change when moving to a new ROM. Feel free to use this for your OBS layout.

Future builds will hopefully have the following:

1. Ability to determine a swap order rather than having games shuffled.
2. Code cleanup.
