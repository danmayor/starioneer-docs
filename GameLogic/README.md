# Starioneer Game Logic Jobs
We will leverage the Unity Job system to run our "ai" logic on background threads to best leverage the capabilities of the players device. This will be defined more as we get into the specifics of each job, but as an idea of what these are:

- Mining Job (Controls flight, mining, and delivery or AI mining ships)
- Market Job (Controls the trading that happens at a station market)
- Patrol Job (Controls an AI patrol vessel)

...

General idea, our "AI" will be a job that takes an array of game objects, calculate some basic outcomes and call functions on the Ship, and Station objects to drive our game.

[<< Back: Home](../README.md) || [Next: Space Ships >>](../Ships/README.md)

