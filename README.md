An enhanced and extensible version of Conway's GOL


Game rules:

Every cycle, every LifeForms updates
* LifeForms die if they have 0 health

* Animals
    * can move
    * can consume other LifeObjects
* Plants
    * can't move
    * Seeds grow into plants based on conditions
    * Seeds remain after the plant grows
* Non-rival LifeObjects can occupy the same position


To support a new species, extend some subclass of LifeObject in the Species package.

ConwayPlant/ConwaySeed is an example of a Seed/Plant relationship
WeakPredator is a good example of an Animal

To add a new species to the simulation, edit LifeWorld.populateWorld() 

To change the simulation size, edit the main method in LifeWorld (which is the main class).
 
