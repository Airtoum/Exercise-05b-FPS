# Exercise-05b-FPS
Exercise for MSCH-C220, 29 March 2021

The first Godot 3D exercise, a simple first-person-controlled character with some CSG terrain.

I set the input_dir's y value to 0 before normalizing it so that the player's speed remained constant rather than changing based on how far you were looking up or down. An altered system would still be necessary in order to allow looking straight up or down, where it looks only at the player's rotation on the Z axis rather than the camera's transformation matrix. This camera would probably be well suited for a third-person game, or a game without gravity.

## Implementation
Built using Godot 3.2.3

The shotgun model is from the [Weapon Pack](https://kenney.nl/assets/weapon-pack) at kenney.nl.

## References
None

## Future Development
None

## Created by 
Airtoum
