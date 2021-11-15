# Ship Scripts
Each space ship prefab should also attach a Space Ship scipt, this space ship script defines common settings and command handlers that make our ship prefab assets functional within our game. The ship script provides the following:

__Engine Bay__  
The engine bay is an instance of our [EngineBay](./Scripts/EngineBay.md) script. The Engine Bay allows us to configure what type and size of engines can be installed on this ship.

__Generator Bay__  
The generator bay, like the engine bay is where our player can install power generators. Power generators make the energy that we use to charge shields and fire weapons. Is an instance of [GeneratorBay](./Scripts/GeneratorBay.md).

__Shield Emitter Bank__  
The shield emitter bank is where the player can install shield emitters. The bank is an instance of [ShieldEmitterBank](./Scripts/ShieldEmitterBank.md) and defines what type and size of shield emitters can be installed. The ship script allows for an array of shield emitter banks.

__Cargo Hold__  
The cargo hold, e.g. the capacity of how much can be carried, and what is being carried in this ships inventory.

__Scanner__  
The scanner is simply a level representing what level scanners installed on this ship. (Higher levels reveal more on sonar and when scanning)

__Comms__  
The comms is simply a level representing what level of communications array the ship has installed. (Higher levels allow ships to communicate at longer distances, and after meeting aliens can translate allowing ships to communicate with the aliens).

__Hull Strength__  
Current and maximum hull strength of this ship. When zero kablooey it's dead, can be repaired at space stations with repair facilities or at ship yards.

__Flight Control__  
Flight control functionality, specifically this is where we can feed input's into the physics on this ships rigidbody. This will allow us to easily call from our AI jobs as well. Note that this ships mass, drag and angular drag should be set on the rigid body directly (most likely at design time).

__Combat Systems__  
This will need to be fleshed out some more as we go, but need system that allows us to aim primary weapons and fire them, systems for turrets to track and automatically shoot etc.

_(more coming soon)_

[<< Back: Space Ships](./README.md) |
