# Inventory System Item Classes
## Item Types:
### Resources
e. g.: coal, water, crystal, ammunition, plant fibre, wood
- stack limit

### Tools
e. g.: Mining Tools (Drill), Repair Tool, Farming Tools, Jetpack
- energy level
- energy consumption rate

### Clothes
e. g.: armor, functional
- slower water drain
- heat resistance
- better visibility (at night)
- defense increase
- less stamina drain

### Weapons
e. g.: Fernkampfwaffen, Nahkampfwaffen
- range
- cooldown 
- damage
- firerate
- stamina cost

### Consumables
- health increase (positive & negative)
- hunger decrease (positive & negative)
- thirst decrease (positive & negative)
- effect duration
- melee attack buff
- defense buff
- heat resistance buff
- stack limit

### Key Items
e. g.: story related things
- only here to keep in inventory after death
- can’t be removed manually

### Blueprints:
Erstmal machen wir die nicht als Items, sondern als freischaltbare Rezepte am Upgrade-Table

-> eigentlich müssten das ja auch Items sein: aber sie könnten, ähnlich wie die Key Items feststehen und keinen Platz verbrauchen (in einem separaten Tab)

## Videos von `Coding With Unity`
[Scriptable Object Inventory System | Part 1](https://www.youtube.com/watch?v=_IqTeruf3-s&list=PLJWSdH2kAe_Ij7d7ZFR2NIW8QCJE74CyT&index=1)
[Saving and Loading your Inventory with Scriptable Objects | Part 2](https://www.youtube.com/watch?v=232EqU1k9yQ&list=PLJWSdH2kAe_Ij7d7ZFR2NIW8QCJE74CyT&index=2)
[Item Buffs/Stats | Scriptable Object Inventory System | Part 3](https://www.youtube.com/watch?v=LcizwQ7ogGA&list=PLJWSdH2kAe_Ij7d7ZFR2NIW8QCJE74CyT&index=3)
- [ ] go back to item buffs to make random attribute values of food items
[Item Swapping | Scriptable Object Inventory System | Part 5](https://www.youtube.com/watch?v=ZSdzzNiDvZk&list=PLJWSdH2kAe_Ij7d7ZFR2NIW8QCJE74CyT&index=5)
-^-^- perhaps go back here to create the visual representation =^-^=

==How the fuck does the player inventory get the database value?==

- [ ] in the Code Review Video he changes the buffs at `24:00`
## Links
[if number of conditions is more than 5 or so, prefer SWITCH over IF, otherwise use whatever looks better](https://stackoverflow.com/questions/395618/is-there-any-significant-difference-between-using-if-else-and-switch-case-in-c)

## To Do
- [ ] GroundItem should set the sprite of its parent to the sprite of its item
