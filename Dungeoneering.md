# Dungeoneering
- [Exploration Turn Sequence](#exploration%20turn%20sequence)
- [Doors](#doors)
	- [Stuck Doors](#stuck%20doors)
	- [Locked Doors](#locked%20doors)
	- [Magic](#magic)
	- [Doors Swinging Shut](#doors%20swinging%20shut)
	- [Hidden Doors](#hidden%20doors)
	- [Dungeon Denizens](#dungeon%20denizens)
	- [Listening at Doors](#listening%20at%20doors)
- [Movement](#movement)
	- [Exploration Speed](#exploration%20speed)
	- [Hurrying](#hurrying)
- [Resting](#resting)
- [Searching](#searching)
- [Traps](#traps)
- [Random Encounters](#random%20encounters)

## Exploration Turn Sequence
1. GM performs a [Random Encounter](CoreRules.md#Random%20Encounters) check (if needed).
2. The players declare the actions the party will take (moving, searching, listening, opening doors, etc).
3. The GM describes the results of their actions and what they see.  If a monster is encountered, play proceeds to the Encounter phase.
4. The GM and players perform any needed bookkeeping: advancing the Torch Timer, tracking spell durations, etc.

## Doors
Constructed dungeons (as opposed to natural caverns) will frequently have doors blocking access to different parts of the dungeon.  Depending on the environment of the dungeon (such as damp conditions), doors may be swollen and become stuck. The scenario will typically indicate if a door is stuck or not, but if such is not designated, the GM should assign a chance in 10 of any given door being shut (3 in 10 for the "typical" dungeon).

### Stuck Doors
A stuck door may be forced with a **Strength** check vs an appropriate [difficulty](RulesSynopsis.md#difficulty%20targets) (most should be in the Easy/9+ to Tricky/15+ range).  If the check is failed, the party loses any chance to surprise any creatures lurking on the opposite side.  Forcing a stuck door also counts as a loud event, possibly prompting a check for [random encounters](CoreRules.md#random%20encounters).

### Locked Doors
These may be forced in the same manner as a stuck door.  Alternatively, a character with the appropriate tools (and training helps) may attempt to pick the lock.  This is a [Skilled](RulesSynopsis.md#Skilled%20Check) **Dexterity** check vs. the lock's [difficulty](RulesSynopsis.md#difficulty%20targets).  Typically only [Rogues](classes/Rogue.md) and [Hybrid-Rogues](Glossary.md#Hybrid%20Class) are considered skilled in this activity.

### Magic
There are also [spells](magic/Spells.md) capable of opening locked or stuck doors (such as the [Open](magic/TierZeroSpells.md#open) cantrip).

### Doors Swinging Shut
Again, most scenarios will indicate if a door will swing shut if left open.  If not explicitly called out by the scenario, assume a 7 in 10 chance that the door will swing shut if not propped open in some way.

### Hidden Doors
Concealed and Secret doors are both types of **hidden doors**.  The only real difference is that a secret door will be disguised as part of the environment (such as the classic swinging bookcase) while a concealed door is simply hidden behind some obscurement (such as a tapestry) but is obvious once the obscuring item is removed.  In either case, these doors will not be noticed unless the character is actively searching the area.  Concealed doors are frequently easier to detect than secret doors.

When searching an area containing a hidden door, the GM secretly rolls a [Perception check](CoreRules.md#Perception) for the searching character(s) vs. the hidden door's [difficulty](RulesSynopsis.md#difficulty%20targets).  If the check is a success, the character's will know that a door is there, but not necessarily how to open it.

### Dungeon Denizens
It should be assumed that any denizens living in the dungeon will know how to open any locked/stuck doors easily.  They should also know the location of most (if not all) concealed and secret doors.  Creatures not living in the dungeons will frequently find themselves facing the same obstacles as the player-characters.

### Listening at Doors
Only one character at a time may listen at any given door (or two for a double-door; considered as [helping](CoreRules.md#Helping)). The listening character makes a [Perception](CoreRules.md#Perception) check using their hearing (if any particular bonuses or penalties apply; such as [Deafness](Combat.md#Deafened)) vs a **difficulty** determined by the GM.  If there are creatures on the other side of the door, and they are attempting to be [stealthy](CoreRules.md#Stealth), this is resolved as a [Contested Check](CoreRules.md#Contested%20Checks) vs. stealth.  The referee should roll this check as the player-characters would not know if they failed or if there is simply nothing on the other side of the door.

## Movement
### Exploration Speed
When moving through a dungeon and remaining alert for danger and clues, the party moves at the rate of the slowest character times 3 every [Exploration Turn](RulesSynopsis.md#Time); thus a character with a move of 30ft can cover 90ft per Exploration Turn.  This may seem slow, but takes into account that the characters are remaining alert for danger and will get their full perception chances (rolled or passive).

### Hurrying
If the party wishes, they can triple their **Exploration Speed** but they suffer disadvantage on all perception checks.  Additionally, this pace may not be kept up indefinitely and each character will need to make an [Exhaustion](CoreRules.md#exhaustion) check at the end of each [Exploration Turn](RulesSynopsis.md#Time).  The **difficulty** of the check is 9 + 3 per consecutive **Exploration Turn**.

## Resting
Characters must take at least one [Short Rest](Combat.md#Short%20Rest) every [Watch](RulesSynopsis.md#Time) when travelling (both in and out of dungeons).  Any character that fails to do so must pass an [Exhaustion Check](CoreRules.md#exhaustion) vs **difficulty 12** or gain 1 level of [Exhaustion](Combat.md#Exhaustion).  This check must be repeated every hour until they take a short rest with the difficulty increasing by 2 for each consecutive check.

## Searching
A character can search a single 10ft x 10ft area in one [Exploration Turn](RulesSynopsis.md#time).  The searching character makes a [Perception](CoreRules.md#Perception) check vs the **difficulty** of any hidden items/creatures in the area (see the [Helping](CoreRules.md#Helping) rules if multiple characters search the same area).  The GM should make this roll as the player-characters have no way to know if they failed in their search of if there really is nothing there.  A given area can only be searched once unless the character(s) manage to arrange an additional bonus they didn't have before (including going up a level and increasing their **Skill Bonus**).

## Traps
Traps are one of the many defenses the makers of dungeons put in place to protect it from invaders.  Traps may appear on/around treasures or in the rooms and corridors of the dungeon itself.  Any given trap should have the following information:
- **A Tell:** Most traps should have some sort of hint or clue to their existence if not to how they work (such as bloodstains, scorch marks or whatever else seems appropriate to how the trap works).
- **Concealment:** This defines how the trap is hidden and the Difficulty Target to find the trap when a character is searching the area or item that has been trapped.
- **Trigger(s):** This defines the action(s) that will potentially set off the trap and what is the chance of it going off (typically expressed as an X in 10 chance).  This should also include the means to bypass the trap (if any exists).
- **Effect(s):** What happens when the trap does go off.  This should also indicate if the trap allows a saving throw (including type and difficulty) or must make an attack roll (along with the attack modifier) vs. the victim's AC.
- **Description:** This should describe not only the trap mechanism but also its purpose.

Most denizens living in the dungeon should already be aware of any traps and how to properly disarm or bypass them (along with how to reset them).

_**Example**<br/>_
*A Crossbow Trap {spot: diff 13 (wall)/diff 15 (lock); attack: +3/1d8p} will be set off if anyone enters the room via the door without first turning the lock two full revolutions.  The bolt is fired from the wall behind anyone trying to open the door.  The dead body slumped against the door with a crossbow bolt in its back is a testament to the trap's effectiveness.*

## Random Encounters
**Frequency:** In a typical dungeon, a check to experience a random encounter (wandering monster, strange noises, rival adventurers, etc) should be made once every 3 [Exploration Turns](RulesSynopsis.md#Time).

**Chance:** Normal odds for most dungeons should be 1 in 6.

**Distance:** The source of the encounter will be 2d6x10 feet away (or the furthest distance that can be percieved).  Roll 1d6 to determine the encounter's direction of travel (if any):
- 1-3: moving toward the party
- 4-5: moving away from the party
- 6: stationary

## Evasion and Pursuit
Compare both sides' movement rates.
- If the fleeing side is faster, they will automatically escape.
- If the fleeing side is not faster, proceed to the **Pursuit** rules below.

### Pursuit
Just like with [Combat](Combat.md), **Pursuit** time is measured in [Rounds](Combat.md#Time).

Each side is assumed to be **Running** at 3 times their base movement speed.  This pace may be kept up for a number of **Rounds** equal to the creature's **Constitution** score.  After this, the creature must make an [Exhaustion](CoreRules.md#exhaustion) check at the start of every Round with a **diff** equal to 9 + 3 per consecutive Round.  Once a creature gains any levels of exhaustion, they can no longer run.

Most NPCs will stop pursuit if they loose sight of the fleeing party.  Make a [Reaction Check](CoreRules.md#charisma%20and%20reactions) and on a **Hostile** result, the NPCs will continue pursuit as best they can.

#### Distractions
A fleeing party may attempt to distract their pursuers by dropping treasure or food (whatever they think will work best).  If the GM determines the distraction is worth notice, there is a roughly 50% chance the pursuing party will stop.  Likewise, dropping an obstacle (like burning oil or caltrops) may discourage or slow pursuit.
