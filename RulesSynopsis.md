# Rules Synopsis
- [D20 Checks](#D20%20Checks)
	- [Ability Check](#Ability%20Check)
	- [Skilled Check](#Skilled%20Check)
	- [Attack Roll](#Attack%20Roll)
		- [Magical Attack Roll](#Magical%20Attack%20Roll)
	- [Difficulty Targets](#Difficulty%20Targets)
	- [Natural Results](#Natural%20Results)
	- [Automatic Success and Failure](#Automatic%20Success%20and%20Failure)
	- [Critical Results](#Critical%20Results)
	- [Advantage and Disadvantage](#Advantage%20and%20Disadvantage)
	- [Sacrificing for Success](#Sacrificing%20for%20Success)
	- [Repeated Attempts](#Repeated%20Attempts)
	- [Group Tests](#Group%20Tests)
- [Fortune](#Fortune)
- [Names](#Names)
- [Countdown Pools](#Countdown%20Pools)
	- [Countdown Pool Average Number of Rolls](#Countdown%20Pool%20Average%20Number%20of%20Rolls)
- [Die Adjustments](#Die%20Adjustments)
- [Tags](#Tags)
	- [Damage Types](#Damage%20Types)
- [Time](#Time)
- [Rounding](#Rounding)

---
## D20 Checks
D20 checks lie at the heart of the system.  Any time a character attempts an action with a risk and a chance of failure, a **D20 Check** is made.  There are three basic types of **D20 Check**.

### Ability Check
This is the most basic form.  The player simply rolls 1d20 and adds the appropriate **Ability Modifier** and compares the total to the [Difficulty Target](#difficulty%20targets) set by the GM.

Ability Checks involving Strength, Dexterity or Constitution are referred to as **Physical Checks**.

Ability Checks involving Intelligence, Wisdom or Charisma are referred to as **Mental Checks**.

&emsp;1d20 + Ability Modifier >= Difficulty Target

### Skilled Check
In some cases, a character may attempt a task that is directly related to their **Class** or [background](Background.md) **Apprenticeship**.  In these cases, an **Ability Check** is made and the character gets to add 2/3 their level (if single-classed) or 1/2 their level (if a hybrid-class) to the check outcome.  Rogues and hybrid-rogues may gain an additional bonus based on the specific check type.  If neither the character's class nor apprenticeship apply, this is treated as a raw Ability Check at **Disadvantage**, assuming the task is even possible for someone who is unskilled.

&emsp;1d20 + Ability Modifier + Skill Bonus (if appropriate) >= Difficulty Target

### Attack Roll
Whether swinging a sword, firing an arrow or simply punching someone in the face, an attack roll is required for the attacker to do damage to the target.  An **Attack Roll** consists of the player rolling 1d20 plus the character's **Attack Bonus** plus either the character's **Strength** or **Dexterity** modifier (depending on the type of attack).  This must equal or exceed the target's **Armor Class** to be successful.

&emsp;1d20 + Attack Bonus + [Strength or Dexterity] Modifier >= Armor Class

#### Magical Attack Roll
This follows the same procedure as a normal [Attack Roll](#Attack%20Roll), but instead uses the caster's **Skill Bonus** and either **Intelligence**, **Wisdom** or **Charisma modifier**.

&emsp;1d20 + Skill Bonus + [Intelligence, Wisdom or Charisma] Modifier >= Armor Class

### Difficulty Targets
Any given **D20 Check** will be compared to a Difficulty Target.  For attacks, this is typically the target's **Armor Class**.  For other **D20 Checks** (**Ability Checks** and **Skilled Checks**), this will be a value determined by the GM based on how difficult the task is.

|   Difficulty    | Target # |
|:---------------:|:--------:|
|    Very Easy    |    6+    |
|      Easy       |    9+    |
|    Moderate     |   12+    |
|     Tricky      |   15+    |
|      Hard       |   18+    |
|    Very Hard    |   21+    |
|     Heroic      |   24+    |
|    Legendary    |   27+    |
| Nigh Impossible |   30+    |

### Natural Results
Occasionally, the rules will reference a “Natural Roll”.  This is the die face that is showing after the roll, without applying any modifiers.  _For example, if a warrior with a +3 bonus to hit rolls a 12 on the die, their total result is 12+3 = 15.  Their **natural** result is just 12._

### Automatic Success and Failure
It is not uncommon in d20 based systems to apply an 'automatic success' and 'automatic failure' rule for **Natural Rolls** of 20 and 1 (respectively).  This system does not do that with the exception of [Saving Throws](CoreRules.md#Saving%20Throws).

### Critical Results
There is no Critical Failure rule in this system.

Only **Attack Rolls** have a chance of **Critical Success**, which is defined as rolling a natural 20 and exceeding (not meeting) the target's **AC**.

### Advantage and Disadvantage
**Advantage**: When performing a check, roll 2d20 and take the highest.

**Disadvantage**: When performing a check, roll 2d20 and take the lowest.

If a check has both **Advantage** and **Disadvantage** count up the number of each.  If there are more advantages, the roll is made at **Advantage**.  If there are more disadvantages, the roll is made at **Disadvantage**.  If they are equal, the roll is made normally.

### Sacrificing for Success
If a roll is failed, a player may choose to have their character make a sacrifice to succeed.  The severity of the sacrifice will determine the bonus to the check, as determined by the GM.  Nice GMs will let you know if your proposed sacrifice is enough ahead of time and let you either increase it or back out.

### Repeated Attempts
Under normal circumstances, a **D20 Check** may only be attempted a single time, unless  the circumstances are somehow changed enough to grant the character at least an additional +1 bonus (or Advantage) on the check, or a character has a special ability (such as **Fortune Points**) allowing a retry.

### Group Tests
In a circumstance where an entire group must make a check (such as trying to sneak past an enemy patrol), the entire party makes the check against the same **DT**.  If half or more of the party succeeds, the check is counted as a success for everyone in the party; otherwise it's a failure for everyone in the party.

---
## Fortune
A measure of a character’s luck, determination or the hand of fate, **Fortune Points** may be spent in various ways to aid a character and are earned when a character’s [Passions](CharacterCreation.md#passions) affect the character in a negative way.

A character has a **Base Fortune Point** (**BFP**) score equal to their level divided by two (rounded up).  When a character starts play and each time they complete an [Extended Rest](Combat.md#extended%20rest), their **Fortune Points** are set to their **BFP** value, regardless of if they were higher or lower than this value when the rest was started.  A character’s **Max Fortune Point** (**MFP**) score is equal to their level.  If a character would earn more FPs than their MFP, the excess points are lost.

**Fortune Points** may be spent in the following ways.

| Use | Effect |
|:---|:---|
| Help a Friend | If a friend is performing a **D20 Check** that is related to one of your **Passions**, you may spend a **Fortune Point** to take the **Help** action. |
| Second Chance | A FP may be spent to re-roll a failed **D20 Check** so long as that check is in service to one of your **Passions**. Only one die may be re-rolled (thus a roll with **Advantage** or **Disadvantage** only re-rolls 1 of the two dice, not both). |
| Lucky Situation | A FP may be spent to use something in the environment to your advantage, or introduce a reasonable element that can be used. For example, a nearby hay stack may be used to cushion a fall off the roof of a building. This must be in service to one of your **Passions**. |
| Cheat Death | A character who has reached 0 HP, may spend a FP to automatically stabilize and not need to continue rolling their [Death Pool](#the%20death%20pool). However, they are still at 0 HP and unconscious. This may always be done, even if not directly related to a **Passion**. |
| Special Ability | Certain **[Traits](Traits.md)** and **Class Abilities** require the expenditure of a FP to activate. This may always be done, even if not directly related to a **Passion**. |

---
## Names
All creatures have a common name, which they will use freely.  Supernatural creatures (including spellcasters) also have a **True Name**, which they keep secret.  Knowing a supernatural creature’s true name, gives one power over it and makes one more resistant to its supernatural abilities.  Typically this is expressed via the **Advantage** and **Disadvantage** mechanics.

---
## Countdown Pools
Occasionally, the rules will call for the formation of a **Countdown Pool**.  Typically this is expressed in the form of "#p#" followed by a time unit (such as 2p6 minutes).  This is a pool of dice that are rolled at every specified time increment.  Each die that comes up a ‘1’ is removed from the pool.  When all dice have been removed from the pool, whatever effect is indicated by the countdown pool completes.

### The Death Pool
One special **Countdown Pool** is the **Death Pool**.  A death pool is a number of 4-sided dice equal to the creature's **Constitution Modifier** plus its **Wisdom Modifier**; with a minimum pool size of 1.  This is rolled at the end of each of the creature's [Turns](Combat.md#time) and when the pool is empty, the creature expires.

### Countdown Pool Average Number of Rolls

| Pool Size | D6 | D4 | D3 | D2 |
|:---:|:---:|:---:|:---:|:---:|
| 1 | 3-4 | 1-2 | 1-2 | 1-2 |
| 2 | 7-8 | 4-5 | 3-4 | 2-3 |
| 3 | 9-10 | 6-7 | 4-5 | 2-3 |
| 4 | 11-12 | 7-8 | 5-6 | 3-4 |
| 5 | 12-13 | 8-9 | 5-6 | 3-4 |
| 6 | 13-14 | 8-9 | 6-7 | 3-4 |

---
## Die Adjustments
Occationally the rules will call for a die type to be stepped up or stepped down.  Use the table below to find the current die type and move left if the die type is being reduced or right if it's being increased.

| Dice Progression |
|:----------------:|
| d2 => d3 => d4 => d5 => d6 => d8 => d10 => d12 => d16 => d20 |

- For a d2, roll 1d4 and divide the result in half, rounding up.
- For a d3, roll 1d6 and divide the result in half, rounding up.
- For a d5, roll 1d10 and divide the result in half, rounding up.
- For a d16, roll 1d4 and 1d8.  If the d4 is 3-4, add 8 to the d8 roll.  Otherwise add 0.

---
## Tags
Most everything in the game world has one or more tags.  These are a game-mechanic concept and have no representation within the game world.  By themselves, tags do not have any mechanics tied to them.  However, other rules (special abilities, supernatural powers, etc.) may have effects specific to particular tags.

*For example: an [elf](species/Elf.md) character has the “humanoid” and “fae” tags.  Any ability or power referencing either “humanoid” or “fae” will affect an [elf](species/Elf.md).  However, something that only affects creatures with the “undead” tag would not affect the [elf](species/Elf.md).*

### Damage Types
Damage Types are a particular form of Tag that denotes the nature of the damage an attack does.  Different creatures may be resistant or vulnerable to one or more types of damage.

Here is a list of common damage types: 
- **Acid** – Caustic damage that dissolves the target, such as a Gelatinous Cube’s digestive enzymes.
- **Blunt** – Blunt trauma, such as from a fall, a club, etc.
- **Cold** – Damage caused by extremely cold temperatures, such as a Frost Dragon’s breath.
- **Fire** – Burning damage from heat, such as a torch or a Fire Dragon’s breath.
- **Lightning** – Any form of electrical damage, such as from a lightning bolt.
- **Necrotic** – Damage directly to a creature’s life force (such as the aging touch of a ghost) or any effect that necrotizes the flesh (such as a wraith’s touch).
- **Piercing** – Damage that pierces the skin, such as arrows and spears.
- **Poison** – Venoms and toxins, such as a spider or snake bite.
- **Radiant** – Damage caused by high intensity light (such as a laser or an angel’s battle aura).
- **Slashing** – Damage that cuts open the target, such as from an ax.
- **Spirit** - Damage that directly affects a creature's spirit or mind, such as a Lich's soul drain.
- **Thunder** – Sonic damage that both shocks the senses and rattles the bones.

---
## Time
Time is broken up into three broad categories: **Combat Time**, **Exploration Time** and **Narrative Time**.  

**Combat Time** is measured in **Combat Turns** (one creature’s chance to move and act), **Rounds** (the combined Turns of all participants; approximately 6 seconds) and **Minutes** (1 minute = 10 Rounds).  

**Exploration Time** is measured in **Exploration Turns** (approximately 10 minutes), **Hours** and **Watches** (4 Hours).  

**Narrative Time** is not strictly tracked and, instead, the GM determines how much time has passed once the narration is concluded.  

*For example, a group traveling a well-known safe road from one town to the next may take a full day’s travel.  The GM should declare this as narrative time and simply inform the group that 1 day of travel has passed.  On the other hand, if the group is traveling through a dangerous wilderness where they may be ambushed by monsters or other enemies, it’s recommended that this be treated as Exploration Time tracked in either Hours or Watches as the GM deems appropriate.  Similarly, if the group is exploring a dungeon, 10 minute Exploration Turns would be called for.*

### Time Steps
Occasionally, the rules will call for the time something takes to be moved up or down one step:
- 1 Reaction
- 1 Action
- 1 Round
- 1 Minute
- 1 Exploration Turn (10 minutes)
- 1 Hour
- 1 Watch (4 hours)
- 2 Watches (8 hours)
- 1 Day
- 1 Week
- 1 Fortnight (2 weeks)
- 1 Month
- 1 Season (3 months)
- 1 Year
- double the number of years for each additional step.

---
## Rounding
Unless stated otherwise, the common convention is to round decimal values of 0.5 or greater up to the nearest whole number.  Values less than 0.5 are rounded down to the nearest whole number.
