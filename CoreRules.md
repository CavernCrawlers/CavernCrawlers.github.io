# Core Rules
The earlier [Rules Synopsis](RulesSynopsis.md) provided a quick overview of the base game mechanics. In this chapter we'll go into more details about the rules and procedures for implementing them in your games.

## The D20 Check
The core mechanic of this system is the **D20 Check**.  There are three broad types of D20 check: the **Ability Check**, the **Skilled Check** and the **Attack Roll**.  An Ability Check is the roll of a 20-sided die, modified by the character's relevant **Ability Modifier** and then compared to a target difficulty.  Skilled Checks and Attack Rolls can be consider sub-types of the Ability Check, which add in a character's **Skill Modifier** or **Attack Bonus** (respectively).

### When to Roll
Add D20 Check should only be called for when there is both doubt as to the action's success and consequences for failure.  If the outcome is a given (either success or failure), there is no need to roll.  Likewise, if there is no consequence for failure the actor can take as much time as they need to succeed, so success should simply be assumed unless the action is impossible.

### Modifiers
Situational arithmetic modifiers should generally be applied to the target DT rather than the die roll itself.  Typically these will range from +5 (for an exceptionally difficult task) to -5 (for an exceptionally easy task) with +3 to -3 being much more common.

### Flavor Bonus
Providing a rich and exciting description of how your character accomplishes an action is worth a small  (+1 or +2) bonus on the D20 check.  Note, however, this should be a unique description; simply repeating the same description over and over is not worth a bonus.

### Advantage and Disadvantage
In cases where multiple factors combine to make a task generally easier or harder but no hard and fast numeric modifier exists, the roll should be made either with **Advantage** or **Disadvantage**. Otherwise see the earlier primer on [Advantage and Disadvantage](RulesSynopsis.md#Advantage-and-Disadvantage) for additional details.

### Contested Checks
When two individuals are working against one another, a **Contested Check** is called for.  Each party performs a **D20 Check** as described above.  Whomever has the highest total is the winner of the contest.  In the event of a tie, **Advantage** beats Normal beats **Disadvantage**.  If still tied, whomever has the highest total bonus to their roll wins.  If still tied, re-roll if a tie result does not make sense for the situation.

Some contests require multiple checks to resolve.  For example, a long foot race may require 3 total checks to complete.  In this case, whomever achieves the most victories is considered the overall winner.

### Passive Checks
In cases where a **passive check** is called for, the check is made with an assumed d20 roll of 8.  Thus, a character’s ‘Passive Perception’ check would be 8 + WIS bonus.

It is helpful to have the following passive checks written down ahead of time:  **Perception**, **Insight** and each **Saving Throw**.

### Saving Throws
Saving throws are a specialized type of **D20 Check**.  The saving throw modifier is applied to the d20 roll along with an appropriate ability modifier.  
- **Evasion** saving throws add the highest of the character’s **Dexterity** or **Intelligence** modifiers
- **Hardiness** uses **Strength** or **Constitution**
- **Spirit** uses either **Wisdom** or **Charisma**

Unlike other D20 Checks, a **natural 1** always results in a failure on a Saving Throw and a **natural 20** is always a success.

## Charisma and Reactions
A **Reaction Check** is made upon the PCs meeting an NPC or group of NPCs for the first time and how they may react is uncertain.  Unlike other D20 Checks, this is not a simple pass/fail test.  Instead the D20 is rolled and the spokesperson's **Charisma Modifier** is added to the roll.  If the NPC group is inclined to be hostile, the roll is made with **Dissadvantage**.  If they are already inclined to be friendly, the roll is made with **Advantage**.  Most groups are neutral and will simply be a standard roll.  Compare the total rolled to the table below.

### Reaction Check Result Table
| d20      | Result |
|:---------|:-------|
| 1-       | **Hostile:** Will either attack or otherwise attempt to thwart the PC. If hostile action is not possible or obvious suicide, will attempt -to flee or get help. |
| 2 to 6   | **Unfriendly:** Will either attack or otherwise thwart the PCs if the NPCs have the upper hand. Otherwise will watch the PCs warily to see what they do. |
| 7 to 14  | **Neutral:** The NPCs are undecided and will keep a watch on what the PCs do before deciding on their own course of action. |
| 15 to 19 | **Indifferent:** Open to friendly negotiation or simply going about one another’s business unmolested. |
| 20+      | **Friendly:** Willing to cooperate with the PCs and even provide assistance if such is not dangerous or too costly. |

## Hazards and Challenges
### Climbing
Characters can normally climb at a rate equal to half their ground movement, assuming sufficient handholds and calm, dry conditions.  Should conditions become truly hazardous (such as rainfall, high winds or or similar), a Dexterity Check should be called for, with an appropriate DT.  If the check fails, the character will fall.
#### Long Climbs
For very long climbs (more than around 30 feet), multiple checks should be made (typically about one every 30 feet or so).
#### Sheer Surfaces
Very steep or sheer surfaces cannot normally be climbed without specialized climbing equipment.  Rogues have a special ability to climb such surfaces without needing specialized gear.
### Visibility
Adventurers frequently find themselves in dark and dim conditions, whether at night or under ground.
#### Dim Lighting/Obscurement
There are conditions in which there is some light but visibility is still restricted.  Such conditions include mists/fog, full moon nights, torches and lanterns being roughly a room away and so forth.  In these conditions sight-based checks and ranged attacks are made at **Disadvantage**.
#### Darkness
When there isn't even dim lighting (such as underground, a moonless or overcast night, and so forth), characters will find themselves in total darkness.  In this case, everyone is treated as if they had the [Blinded](Combat.md#Blinded) conditions.
#### Low-Light Vision
Some beings have eyesight better adapted to dim lighting conditions.  These characters can see in **dim** light as if it were full daylight, except that the vision will be in black-and-white only.  They are still [Blinded](Combat.md#Blinded) by total **darkness**.
#### Darkvision
Some creatures have true Darkvision, allowing them to not only see normally in **dim** lighting (they can still discern color in dim lighting) they also treat full **darkness** as normal creatures would treat dim lighting.
### Falling
Falling from a height onto a hard surface inflicts blunt damage onto the falling creature.  The following table denotes how much damage a creature takes when falling from a given height, as well as how long that fall will take.

| Time   | Velocity | Dist    | Damage | Notes       |
|-------:|---------:|--------:|-------:|:------------|
| 0.40s  | 10fps    | 3ft     | 1d6    |             |
| 0.60s  | 20fps    | 6ft     | 2d6    |             |
| 0.90s  | 30fps    | 13ft    | 3d6    |             |
| 1.20s  | 40fps    | 23ft    | 4d6    |             |
| 1.60s  | 50fps    | 41ft    | 5d6    |             |
| 1.90s  | 60fps    | 58ft    | 6d6    |             |
| 2.20s  | 70fps    | 77ft    | 7d6    |             |
| 2.60s  | 80fps    | 108ft   | 8d6    |             |
| 3.00s  | 90fps    | 144ft   | 9d6    |             |
| 3.40s  | 100fps   | 185ft   | 10d6   |             |
| 3.80s  | 110fps   | 231ft   | 11d6   |             |
| 4.30s  | 120fps   | 296ft   | 12d6   |             |
| 4.80s  | 130fps   | 369ft   | 13d6   |             |
| 5.40s  | 140fps   | 467ft   | 14d6   |             |
| 6.00s  | 150fps   | 576ft   | 15d6   | 1 Round     |
| 7.00s  | 160fps   | 784ft   | 16d6   |             |
| 8.20s  | 170fps   | 1,076ft | 17d6   |             |
| 10.00s | 180fps   | 1,600ft | 18d6   |             |
| 15.60s | 190fps   | 3,894ft | 19d6   | Terminal V. |


