#Resource Damage Model
A resource damage model is how the player's is able to deal with damage to a resource. The most common usage of this is the loss of health or armour. Both of which are just resources to be spent.

The following steps along the spectrum exist:
- Fixed number of units
- Limited recovery system
- Full recovery system
- Regeneration system
- Invulnerability / No damage model

### Fixed number of units
The resource can sustain a number of hits before it has been completely depleted. A special case is when the number is one which results in a **touch is death** situation

###### Examples
- [Bit.TRIP Runner](/games/bit.trip-runner) - If the player touches any part of the world the run ends.
- [Missile Command](/games/missile-command) - Each of the cities the player must defend represent 'health'.

### Limited recovery system
A limited recovery system where it isn't possible to regenerate back to full capacity. This could be done by a reduction in the total resource capacity or by having resource recovery kits (i.e. medkit) return only a proportion of the depleted capacity.

###### Examples
- [XCOM Enemy Unknown](/games/xcom-enemy-unknown) - TODO: how this works.
- [Left 4 Dead](/games/left-4-dead) - Each medkit returns 80% of your health.
- [F1](/games/f1) - Damage to your car can't always be fixed

### Full recovery system
A full recovery system is one where it's possible to return the resource to full capacity.

###### Examples
- [Super Mario Brothers](/games/super-mario-brothers) - Mario can always eat a mushroom to get himself up to full size.
- [Quake](/games/quake) - Both health and armour resources can be restored to their full amount.
- [Half Life](/games/half-life) - Both health and armour resources can be restored to their full amount.

### Regeneration system
A regeneration system is one where the resource has the capacity to regenerate or renew itself. This often happens over time but will restore the resource to full capacity.

###### Examples
- [Gears of War 2](/games/gears-of-war-2) - The player's health regenerates to full.


### Invulnerability / No damage model
This can feature as a buff during a game (invulnerability in Quake I) or where the resource can never expire. This is common in games where the player cannot die.

###### Examples
- [Loneliness](/games/loneliness) - No damage model
- [Quake](/games/quake) - Invulnerability mode

## Ideas
### Transition
The player starts off with an invulnerable resource (such as health) and because of it outclasses all opponents. Obviously not a complicated game but through the actions of the player, the damage model transitions. **Invulnerability** is stripped away and the player gets a **regeneration system**. This breaks but **full recovery** is possible. This two degrades into a **limited recovery** system. Finally the player only has a **fixed number of units** to spend. Such an approach requires the player to be more mindful of their resource usage over the course of the game.