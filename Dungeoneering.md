# Dungeoneering

## Exploration Turn Sequence
1. GM performs a Wandering [Monster check](CoreRules.md#Wandering-Monsters) (if needed).
2. The players declare the actions the party will take (moving, searching, listening, opening doors, etc).
3. The GM describes the results of their actions and what they see.  If a monster is encountered, play proceeds to the Encounter phase.
4. The GM and players perform any needed bookkeeping: advancing the Torch Timer, tracking spell durations, etc.

## Doors
Constructed dungeons (as opposed to natural caverns) will frequently have doors blocking access to different parts of the dungeon.  Depending on the environment of the dungeon (such as damp conditions), doors may be swollen and become stuck. The scenario will typically indicate if a door is stuck or not, but if such is not designated, the GM should assign a chance in 10 of any given door being shut (3 in 10 for the "typical" dungeon).

### Stuck Doors
A stuck door may be forced with a **Strength** check vs an appropriate **DT** (most should be in the Easy/10+ to Tricky/15+ range).  If the check is failed, the party loses any chance to surprise any creatures lurking on the opposite side.  Forcing a stuck door also counts as a loud event, possibly prompting a check for [wandering monsters](CoreRules.md#Wandering-Monsters).

### Locked Doors
These may be forced in the same manner as a stuck door.  Alternatively, a character with the appropriate tools (and training helps) may attempt to pick the lock.  This is a [Skilled](RulesSynopsis.md#Skilled-Check) **Dexterity** check vs. the lock's **DT**.  Typically only [Rogues](Rogue.md) and [Hybrid-Rogues](Glossary.md#Hybrid-Class) are considered skilled in this activity.

### Magic
There may also be spells capable of opening locked or stuck doors.

### Doors Swinging Shut
Again, most scenarios will indicate if a door will swing shut if left open.  If not explicitly called out by the scenario, assume a 3 in 4 chance that the door will swing shut if not propped open in some way.

### Hidden Doors
Concealed and Secret doors are both types of **hidden doors**.  The only real difference is that a secret door will be disguised as part of the environment (such as the classic swinging bookcase) while a concealed door is simply hidden behind some obscurement (such as a tapestry) but is obvious once the obscuring item is removed.  In either case, these doors will not be noticed unless the character is actively searching the area.  Concealed doors are frequently easier to detect than secret doors.

When searching an area containing a hidden door, the GM secretly rolls a [Perception check](CoreRules.md#Perception) for the searching character(s) vs. the hidden door's **DT**.  If the check is a success, the character's will know that a door is there, but not necessarily how to open it.

### Dungeon Denizens
It should be assumed that any denizens living in the dungeon will know how to open any locked/stuck doors easily.  They should also know the location of most (if not all) concealed and secret doors.  Creatures not living in the dungeons will frequently find themselves facing the same obstacles as the player-characters.

### Listening at Doors
Only one character at a time may listen at any given door (or two for a double-door; considered as [helping](CoreRules.md#Helping)). The listening character makes a [Perception](CoreRules.md#Perception) check using their hearing (if any particular bonuses or penalties apply; such as [Deafness](Combat.md#Deafened)) vs a **DT** determined by the GM.  If there are creatures on the other side of the door, and they are attempting to be [stealthy](CoreRules.md#Stealth), this is resolved as a [Contested Check](CoreRules.md#Contested-Checks) vs. stealth.  The referee should roll this check as the player-characters would not know if they failed or if there is simply nothing on the other side of the door.

## Movement
### Exploration Speed
When moving through a dungeon and remaining alert for danger and clues, the party moves at the rate of the slowest character every Exploration Turn.  This may seem slow, but takes into account that the characters are remaining alert for danger and will get their full perception chances (rolled or passive).

### Familiar Areas
If the party wishes, they can move at three times this rate but they will automatically fail all perception checks.

## Resting
Characters must take at least one [Short Rest](Combat.md#Short-Rest) every [Watch](RulesSynopsis.md#Time) when travelling (both in and out of dungeons).  Any character that fails to do so must pass a **Constitution Check** vs **DT 13** or gain 1 level of [Exhaustion](Combat.md#Exhaustion).  This check must be repeated every hour until they take a short rest with the DT increasing by 2 for each consecutive check.

## Searching
A character can search a single 10ft x 10ft area in one [Exploration Turn](RulesSynopsis.md#time).  The searching character makes a [Perception](CoreRules.md#Perception) check vs the **DT** of any hidden items/creatures in the area (see the [Helping](CoreRules.md#Helping) rules if multiple characters search the same area).  The GM should make this roll as the player-characters have no way to know if they failed in their search of if there really is nothing there.  A given area can only be searched once unless the character(s) manage to arrange an additional bonus they didn't have before (including going up a level and increasing their **Skill Bonus**).

## Traps
Traps are one of the many defenses the makers of dungeons put in place to protect it from invaders.  Traps may appear on/around treasures or in the rooms and corridors of the dungeon itself.  Any given trap will have the following traits:
- **Tell:** Most traps should have some sort of hint or clue to their existence if not to how they work (such as bloodstains, scorch marks or whatever else seems appropriate to how the trap works).
- **Concealment:** This defines how the trap is hidden and the Difficulty Target to find the trap when a character is searching the area or item that has been trapped.
- **Trigger:** This defines the action(s) that will potentially set off the trap and what is the chance of it going off (typically expressed as an X in 10 chance).  This should also include the means to bypass the trap (if any exists).
- **Effect:** What happens when the trap does go off.  This should also indicate if the trap allows a saving throw (including type and DT) or must make an attack roll (along with the attack modifier) vs. the victim's AC.
- **Description:** This should describe not only the trap mechanism but also its purpose.

Most denizens living in the dungeon should already be aware of any traps and how to properly disarm or bypass them (along with how to reset them).

### Example Traps
#### Poison Needle
- **Tell:** A dead body of a previous adventurer slumped in the corner of the room.  A close examination by someone knowledgeable of medicine or healing will reveal that they died of poison.
- **Concealment:** There is a small pinhole next to the lock from which the needle will be fired.  Anyone searching the chest must pass a **DT 15** **Perception** check to spot the trap.
- **Trigger:** Attempting to open the lock without using the correct key.  As this is a well-maintained trap, it will always go off in these circumstances.
- **Effect:** The victim must make a **Hardiness** saving throw vs **DT 15** or become [Poisoned](Combat.md#Poisoned) for 3d4(pool) minutes.  They will also take 1d6 poison damage each minute that the poison remains active.  The victim may repeat their save at the beginning of each minute to resist the effects of the poison.

This is a simple poison needle trap concealed next to the lock of a treasure chest intended to prevent anyone who shouldn't from accessing the chest.

#### Spiked Pit
- **Tell:** The stones in this section of the corridor are a slightly lighter shade of grey than the stone in the rest of the dungeon.  A **passive perception** score of 15 or higher will notice this automatically.
- **Concealment:** The floor has been expertly designed to blend in with the surrounding stone.  Anyone searching the area must pass a **DT 15 perception** check to notice the discolored stones and deduce that this is a trap of some kind.
- **Trigger:** Walking across this section of the corridor has a **3 in 10** chance of triggering the trap.  Anyone hugging the wall on either side (keeping their feet within 1 foot of the wall) will not trigger the trap.
- **Effect:** Anyone falling into the trap will fall 10 feet onto sharpened spikes at the bottom, taking **2d6b** damage from the fall plus another **2d6p** damage from the spikes.  If the victim passes an **Evasion** save vs **DT 13**, they manage to throw themselves to the side and avoid falling in.

This is a 10 foot deep pit lined with spikes hidden under an expertly engineered section of the floor.  Once the trap has been triggered, it will remain open until someone pulls the lever on the eastern wall next to the pit (disguised as a torch sconce).

