# Resources
Resources are a common component in games. Their scarcity drives competion and conflict. Their utility gives actors benefit. 

Resources are either transferable or non-transferable. A transferable resource is one that can be given to another actor. Health is non-transferable while wood is.

Here are some transferable resources:
- Munitions - for being shot at things
- Guns - for shooting bullets
- Wood - for trading, for making into planks, etc.
- Money - for buying goods and services e.g. peanuts
- Rabbits - for making ear muffs and food resources
- Action Points - points to spend on actions during a turn

Here are some non-transferable resources:
- Health - to avoid death the resource of health can be traded away
- Mana - for casting spells
- Carrying capacity - how much an actor can carry
- Sanity - how much of the real world is getting through
- Hunger - how long before the actor starves
- Memorised Spells - what spells are in the actor's head


## Resource Growth
Resources can increase their quantity by growing. For most resources this growing is down in a geometric fashion e.g. 1 unit per day, 20 health per medkit. Here are some options for resource growth rates:

- **Never grows** - This resource never grows
- **Geometric** - 1 coin for 1 unit
- **Logarithmic** - 10 coin for 1 unit, 100 coin for 2 units
- **Fibonnaci** - 1,2,3,5,8,13... 13 coin for 6 unit, 21 coin for 7 unit.
- **Percentage** - 1 unit to increase by 50% or 1 unit to restore 80%

The unit is the result of a growth agent. Here are the resource growth options:

- **Nothing** - Nothing will cause this to resource to grow.
- **Time** - This resource grows over time without influence from anything else e.g. regeneration
- **Place** - This resource grows while in a place e.g. healing pool. Time does play a factor here
- **Resource** - A different resource is traded to make this resource grow. I can trade 1 coin for 5 wood.
- **Action** - An actor's action causes the resource to grow e.g. 'summon cats' or 'lay on hands'

### Examples
###### Nothing
- [Don't Starve](/games/dont-starve) - items when used are worn out.
- [Bit.TRIP Runner](/games/bit.trip-runner) - the player can never acquire more health

###### Time
- [Gears of War 2](/games/gears-of-war-2) - The player's health regenerates to full.
- [Missile Command](/games/missile-command) - The player can only fire missile so fast. This cooldown between shots is the resource regenerating.

###### Place
- [F1](/games/f1) - Damage to your car can be fixed in the pits.

###### Resource
- [Super Mario Brothers](/games/super-mario-brothers) - Mario can  eat a mushroom to get himself up to full size (health).
- [Left 4 Dead](/games/left-4-dead) - 80% of health can be restored by using a medkit.

###### Action
- [Eye of the Beholder](/games/eye-of-the-beholder) - The Paladin's 'lay on hands' increases health in another.


## Resource Depletion
As exciting as resource growth is, resource depletion is more common due to 'using' resources. The resource depletion rates options are the same for resource growth.

- **Never grows** - This resource never depletes
- **Geometric** - 1 coin for 1 unit
- **Logarithmic** - 10 coin for 1 unit, 100 coin for 2 units
- **Fibonnaci** - 1,2,3,5,8,13... 13 coin for 6 unit, 21 coin for 7 unit.
- **Percentage** - 1 unit to increase by 50% or 1 unit to restore 80%

The resource depletion agents are also similar with the addition of 'use'.

- **Nothing** - Nothing will deplete this resource.
- **Time** - This resource depletes over time without influence from anything else e.g. decay
- **Place** - This resource depletes while in a place e.g. health in lava or sanity in R'lyeh. Time does play a factor here
- **Resource** - A different resource is traded to make this resource deplete. I may eat rotten food at the cost of health and the benefit of reduced hunger.
- **Action** - An actor's action causes the resource to deplete e.g. moving reduces energy.
- **Use** - A resource can be used and in the process consuming it. I cat eat some meat or I can trade health to stay alive.

### Examples
###### Nothing
###### Time
###### Place
###### Resource
###### Action
###### Use

## Resource Capacity
Every resource has, initially, a capacity. The capacity is different from quantity and represents the maximum potential quantity. The capacity influences how much of a resource can exist in any one place.

Capacity is one of the following:
- **Fixed** - the capacity never increases or decreases.
- **Contracts** - the capacity can decrease but never increases.
- **Expands** - the capacity can expand but never decrease.
- **Fluid** - the capacity can both expand and contract.

The capacity is either zero, a positive number or infinity.

### Examples
###### Fixed
- [Quake](/games/quake) - All resources: health, ammo and shield can be restored to their full amount.
- [Left 4 Dead](/games/left-4-dead) - Ammo can be restored to it's full capacity.
- [Pid](/games/pid) - All resources (except star) can be restored to full amount.

###### Contracts
F1 - car damage

###### Expands

###### Fluid
Dont Starve - carry capacity


# Resource Damage Model
A resource damage model is how the player's is able to deal with damage to a resource. The most common usage of this is the loss of health or armour. Both of which are just resources to be spent.

The following steps along the spectrum exist:
- Fixed number of units
- Limited recovery system
- Full recovery system
- Regeneration system
- Invulnerability / No damage model

### Fixed number of units
The resource can sustain a number of hits before it has been completely depleted. A special case is when the number is one which results in a **touch is death** situation

### Limited recovery system
A limited recovery system where it isn't possible to regenerate back to full capacity. This could be done by a reduction in the total resource capacity or by having resource recovery kits (i.e. medkit) return only a proportion of the depleted capacity.

###### Examples
- [Left 4 Dead](/games/left-4-dead) - Each medkit returns 80% of your health.

### Full recovery system
A full recovery system is one where it's possible to return the resource to full capacity.

###### Examples
- [Super Mario Brothers](/games/super-mario-brothers) - Mario can always eat a mushroom to get himself up to full size.

### Regeneration system
A regeneration system is one where the resource has the capacity to regenerate or renew itself. This often happens over time but will restore the resource to full capacity.


### Invulnerability / No damage model
This can feature as a buff during a game (invulnerability in Quake I) or where the resource can never expire. This is common in games where the player cannot die.


## Ideas
### Transition
The player starts off with an invulnerable resource (such as health) and because of it outclasses all opponents. Obviously not a complicated game but through the actions of the player, the damage model transitions. **Invulnerability** is stripped away and the player gets a **regeneration system**. This breaks but **full recovery** is possible. This two degrades into a **limited recovery** system. Finally the player only has a **fixed number of units** to spend. Such an approach requires the player to be more mindful of their resource usage over the course of the game.