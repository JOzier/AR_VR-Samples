# Google-VR-Anubis-Maze

Virtual Reality Maze Game Using Unity 3D and GVR.

## Video

Gameplay from the start to the end.

[![Alt text](https://i9.ytimg.com/vi_webp/AtpBd8wzgTU/mqdefault.webp?v=63d19067&sqp=CJygxp4G&rs=AOn4CLAduS54Mdrv3V4XkgK4rIayZnDzjg)](https://youtu.be/AtpBd8wzgTU "Click to play on youtube.com")

## Main Components

1. **Waypoint Navigation :** Waypoints is how the user moves through the maze. They become highlighted when the user looks at them - and when clicked they play a sound and move the user to their location.

2. **Collectables :** Along the paths and between the waypoints are gold objects that can be collected. They play a sound and spawn some particles when you click on this and collect them.

3. **The Gate :** A barrier that blocks the path to exit. Once you have the key and put it on its position the door animates open and unblocks the path.

4. **The Key :** Somewhere within the maze, out of sight of the gate, is a key which unlocks it. You must collect it manually, looking at it to highlight it and clicking on it to retrieve it. Once triggered, it plays a sound and spawns some particles to show it's being collected. Once you have the key you can return to the gate and make your way to the finish.

5. **The UI :** At the key positions, at the locked door, and at the final destination to give hint to the user.

6. **The final treasure :** At the end there is Elixir of Life. it becomes highlighted when the user looks at them - and when clicked it reloads the scene to its original state.

## Software

* **Game Engine :**
  * [Unity 3D](https://unity3d.com/) 5.5.1f1.
* **Packages :**
  * [Google VR SDK for Unity](https://developers.google.com/vr/unity/).
  * [Unity Standard Assets](https://www.assetstore.unity3d.com/en/#!/content/32351).

## Target Platform

The main target platform is Android mobiles to use it with cardboard viewer.

## Scripts

All scripts are written by me except for the Waypoint script where I used Udacity provided script and edited on it to make it acts as I needed.

## Art

All models and textures was made by me.  

## sounds

All sounds used was from internet for free.

## Particle Systems

Custom fire particle system was used from standard assets.

## Notes

This Project was required for Udacity _**VR Software Development Course**_ in [Instructors Chris Birke, Austin McCasland, Matt Sonic and Content Developer Vasanth Mohan](https://learn.udacity.com/courses/ud1014).


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
