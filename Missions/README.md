# Missions
There are a variety of missions throughout the game. We need a system that can track progress, provide rewards and unlock content / missions. This mission system may evolve over time but the general design is:

__MissionLog__ is a global parent object that contains a collection of missions.

__Mission__ is an object defining a mission, such as where it is offered, what it's unlocking requirements are and a collection of mission steps the player must complete etc.

__MissionStep__ is an object defining a task that the player must complete within a mission.


[<< Back: Space Stations](../Stations/README.md) || [Next: Economy >>](../Economy/README.md)
