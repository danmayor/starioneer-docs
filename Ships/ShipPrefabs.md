# Ship Prefabs
In this section we discuss Space Ship prefabs, which we mean the root game object, and child assets that define the in game visual representation of a space ship. 

Ship prefabs should be modular and need to provide some specific components to help drive our limited customization systems.

__Command Position__  
Command position should be an empty node that is positioned within the cockpit of the space ship. This is where we will attach the camera when our player is piloting this ship.

__Weapon Mounts__  
Weapon mounts should be empty nodes that are positioned where the player could add weapons. This is where we will attach weapon prefabs in game and is used when determining where to emit particles from when firing the weapon mounted in this position. Related script [Weapon Mount](./Scripts/WeaponMount.md).

_(more coming soon)_

[<< Back: Space Ships](./README.md) |
