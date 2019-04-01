# iDBattleRoyale
Battle Royale Template for UE4

The example map uses the following content packs:
- Starter Content
- Soul Cave
- Soul City

Check out instructions in Game Plan for how to set up and use the project.

## Changes for 2019 Season:
New Gameplay:
- Added health kit and building material pickups
- Health kits heal after a use time and prevent shooting while being used
- Building materials can be used to place simple structures like walls, ramps, floors
- Placed structures can be shot and destroyed.
- Jump pad blueprint that can be placed in your maps.

Circle
- Circle code cleaned up, redundant code removed, some comments added.
- Circle-related variables now have tooltips explaining their use.
- The ThirdPersonGamemode will now search for a death zone actor when the map starts. If it's found, it uses that instead of spawning one. You can use this to manually decide where the circle starts.
- Added a boolean variable to the gamemode that controls whether the circle is used at all. Disabling it lets you run just straight up deathmatch.

Other
- Organized variables into categories to make it easier to tell which ones students should modify for gameplay purposes.
