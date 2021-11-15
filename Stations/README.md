# Space Stations
Space stations serve as transportation, production, and trade hubs in the universe. Space stations may provide one or more services such as:

__Storage Module__  
Every station has a storage module. The commodities that the station itself owns reside here. Space stations attach [StorageModule](./Scripts/StorageModule.md) script and configure total storage space property.

__Market Module__  
Every station has a market module. It's where the station sells it's products and purchases it's resources / input commodities. The market module will contain lists of going rates, background ai jobs will set the rates based on supply and demand. (More on this coming soon)

__Refinery Module__  
Refinery modules will consume raw resources from the stations storage module and convert them into building resources, which are then placed back into the storage module and can be sold via the market module.

__Assembly Module__  
Assembly modules consume building resources from the stations storage module and convert them into products. Products are sold via the market module. Some advanced assembly modules may require products from assembly modules to make their final product.

__Weapon Mounts__  
Same concept as ship weapon mounts.

__Generator Bay__  
Same concept as ship generator bay.

__Shield Emitter Bank__  
Same concept as ship shield emitter bank.

__Combat Control__  
We'll have to define this better as we go, the combat system should allow the player to assume control and cycle through turrets, and for background AI jobs to manage station defense.

_(more coming soon)_


[<< Back: Space Ships](../Ships/README.md) || [Next: Missions >>](../Missions/README.md)
