# Core Rules

The earlier [Rules Synopsis](RulesSynopsis.md) provided a quick overview of the base game mechanics. In this chapter we'll go into more details about the rules and procedures for implementing them in your games.
- [The D20 Check](#The%20D20%20Check)
	- [Ability Check](#Ability%20Check)
	- [Skilled Check](#Skilled%20Check)
	- [Attack Roll](#Attack%20Roll)
	- [Saving Throw](#Saving%20Throw)
	- [Difficulty](#Difficulty)
	- [Natural Roll](#Natural%20Roll)
	- [Automatic Success and Failure](#Automatic%20Success%20and%20Failure)
	- [Critical Results](#Critical%20Results)
	- [Advantage and Disadvantage](#Advantage%20and%20Disadvantage)
	- [Sacrificing for Success](#Sacrificing%20for%20Success)
	- [Repeated Attempts](#Repeated%20Attempts)
	- [Group Tests](#Group%20Tests)
	- [When to Roll](#When%20to%20Roll)
	- [Modifiers](#Modifiers)
	- [Helping](#Helping)
	- [Contested Checks](#Contested%20Checks)
	- [Passive Checks](#Passive%20Checks)
- [Die Adjustments](#Die%20Adjustments)
- [Rounding](#Rounding)
- [Countdown Pools](#Countdown%20Pools)
	- [The Death Pool](#The%20Death%20Pool)
	- [Countdown Pool Average Number of Rolls](#Countdown%20Pool%20Average%20Number%20of%20Rolls)
- [Fortune](#Fortune)
- [Names](#Names)
- [Tags](#Tags)
	- [Damage Types](#Damage%20Types)
- [Charisma and Reactions](#Charisma%20and%20Reactions)
	- [Reaction Check Result Table](#Reaction%20Check%20Result%20Table)
- [Hazards and Challenges](#Hazards%20and%20Challenges)
	- [Climbing](#Climbing)
		- [Long Climbs](#Long%20Climbs)
		- [Sheer Surfaces](#Sheer%20Surfaces)
	- [Falling](#Falling)
	- [Disease](#Disease)
	- [Poison](#Poison)
	- [Starvation](#Starvation)
	- [Swimming](#Swimming)
		- [Drowning](#Drowning)
	- [Visibility](#Visibility)
		- [Dim Lighting/Obscurement](#Dim%20Lighting/Obscurement)
		- [Darkness](#Darkness)
		- [Low-Light Vision](#Low-Light%20Vision)
		- [Darkvision](#Darkvision)
- [Time](#Time)
	- [Time Steps](#Time%20Steps)

---
## The D20 Check
The core mechanic of this system is the **D20 Check**.  There are four broad types of D20 check: the [Ability Check](#ability%20check), the [Skilled Check](#skilled%20check), the [Attack Roll](#attack%20roll) and the Saving Throw.  An Ability Check is the roll of a 20-sided die, modified by the character's relevant **Ability Modifier** and then compared to a target difficulty.  Skilled Checks and Attack Rolls can be consider sub-types of the Ability Check, which add in a character's **Skill Modifier** or **Attack Bonus** (respectively).

### Ability Check
This is the most basic form of *D20 Check*.  The player simply rolls 1d20 and adds the appropriate *Ability Modifier* and compares the total to the [Difficulty](#difficulty%20target) set by the GM.
- Ability Checks involving Strength, Dexterity or Constitution are referred to as **Physical Checks**.
- Ability Checks involving Intelligence, Wisdom or Charisma are referred to as **Mental Checks**.

<p style="text-align:center;"><i>1d20 + Ability Modifier >= Difficulty</i></p>

### Skilled Check
In some cases, a character may attempt a task that is directly related to one of their [Skills](Skills.md).  In these cases, an [Ability Check](#ability%20check) is made and the character adds their [Skill Bonus](Skills.md#skill%20bonus) to the check total.  [Rogues](classes/Rogue.md) and [hybrid-rogues](Glossary.md#hybrid%20class) gain more skills than other classes.  If a **skilled check** is called for, but the acting character lacks the skill, then the skill roll is made as a raw [Ability Check](#ability%20check) at *Disadvantage*, if the GM rules that the check is possible at all.

<p style="text-align:center;"><i>1d20 + Ability Modifier + Skill Bonus >= Difficulty</i></p>

### Attack Roll
Whether swinging a sword, firing an arrow or simply punching someone in the face, an **Attack Roll** is required for the attacker to do damage to the target.  An **Attack Roll** consists of the player rolling 1d20 plus the character's *Attack Bonus* plus either the character's *Strength* or *Dexterity* modifier (depending on the type of attack).  This must equal or exceed the target's *Armor Class* to be successful.

<p style="text-align:center;"><i>1d20 + Attack Bonus + {Strength or Dexterity} Modifier >= Armor Class</i></p>

### Saving Throw
**Saving Throws** are a specialized type of [D20 Check](#the%20d20%20check).  Each *Class* has a *Saving Throw Modifier* that is applied to the d20 roll along with an appropriate *Ability Modifier*.  
- **Evasion** saving throws add the highest of the character’s *Dexterity* or *Intelligence* modifiers
- **Hardiness** uses *Strength* or *Constitution*
- **Spirit** uses either *Wisdom* or *Charisma*

Unlike other *D20 Checks*, a [Natural 1](#natural%20roll) always results in a failure on a **Saving Throw** and a [Natural 20](#natural%20roll) is always a success.

<p style="text-align:center;"><i>1d20 + Saving Throw Modifier + Ability Modifier >= Difficulty</i></p>

### Difficulty
Any given [D20 Check](#the%20d20%20check) will be compared to a **Difficulty**.  For attacks, this is typically the target's *Armor Class*.  For other *D20 Checks* ([Ability Checks](#ability%20check), [Skilled Checks](#skilled%20check) and [Saving Throws](#saving%20throw)), this will be a value determined by the GM based on how difficult the task is.

<table border=2>
    <tr style="background-color:#708090;">
        <th align="center"><b>Difficulty</b></th>
        <th align="center"><b>Target #</b></th>
    </tr>
    <tr>
        <td align="center">Very Easy</td>
        <td align="center">6+</td>
    </tr>
    <tr>
        <td align="center">Easy</td>
        <td align="center">9+</td>
    </tr>
    <tr>
        <td align="center">Moderate</td>
        <td align="center">12+</td>
    </tr>
    <tr style="background-color:#91a3b0;">
        <td align="center">Tricky</td>
        <td align="center">15+</td>
    </tr>
    <tr style="background-color:#91a3b0;">
        <td align="center">Hard</td>
        <td align="center">18+</td>
    </tr>
    <tr style="background-color:#91a3b0;">
        <td align="center">Very Hard</td>
        <td align="center">21+</td>
    </tr>
    <tr>
        <td align="center">Heroic</td>
        <td align="center">24+</td>
    </tr>
    <tr>
        <td align="center">Legendary</td>
        <td align="center">27+</td>
    </tr>
    <tr>
        <td align="center">Nigh Impossible</td>
        <td align="center">30+</td>
    </tr>
</table>

### Natural Roll
Occasionally, the rules will reference a “Natural" roll.  This is the die face that is showing after the roll, without applying any modifiers.  _For example, if a warrior with a +3 bonus to hit rolls a 12 on the die, their total result is 12+3 = 15.  Their **Natural** result is just 12._

### Automatic Success and Failure
It is not uncommon in d20 based systems to apply an 'automatic success' and 'automatic failure' rule for [Natural](#natural%20roll) rolls of 20 and 1 (respectively).  This system does not do that with the exception of [Saving Throws](#saving%20throw).

### Critical Results
There is no *Critical Failure* rule in this system.

Only [Attack Rolls](#attack%20roll) have a chance of **Critical Success**, which is defined as rolling a [Natural](#natural%20roll) 20 and *exceeding* (not meeting) the target's AC.

### Advantage and Disadvantage
**Advantage**: When performing a check, roll 2d20 and take the *highest*.

**Disadvantage**: When performing a check, roll 2d20 and take the *lowest*.

If a check has both *Advantage* and *Disadvantage* count up the number of each.  If there are more Advantages, the roll is made at *Advantage*.  If there are more Disadvantages, the roll is made at *Disadvantage*.  If they are equal, the roll is made normally.

### Sacrificing for Success
If a roll is failed, a player may choose to have their character make a **Sacrifice** to succeed.  The severity of the Sacrifice will determine the bonus to the check, as determined by the GM.  Nice GMs will let you know if your proposed sacrifice is enough ahead of time and let you either increase it or back out.

### Repeated Attempts
Under normal circumstances, a [D20 Check](#d20%20check) may only be attempted a single time, unless  the circumstances are somehow changed enough to grant the character at least an additional +1 bonus (or *Advantage*) on the check. Alternatively a character may have a special ability (such as [Fortune Points](#fortune)) allowing a retry.

### Group Tests
In a circumstance where an entire group must make a check (such as trying to sneak past an enemy patrol), the entire group makes the check against the same [Difficulty](#difficulty).  If half or more of the group succeeds, the check is counted as a success for everyone in the group; otherwise it's a failure for everyone.

### When to Roll
A [D20 Check](#d20%20check) should only be called for when there is both doubt as to the action's success and consequences for failure.  If the outcome is a given (either success or failure), there is no need to roll.  Likewise, if there is no consequence for failure the actor can take as much time as they need to succeed, so success should simply be assumed unless the action is impossible.

### Modifiers
*Situational* arithmetic modifiers should generally be applied to the [Difficulty](#difficulty) rather than the die roll itself.  Typically these will range from +5 (for an exceptionally difficult task) to -5 (for an exceptionally easy task) with +3 to -3 being much more common.

### Helping
Two or more characters working together on a single task will often have greater chances of success than a single character acting alone.  In such a scenario, first determine which character will actually be rolling for the check; this is the "actor".  Anyone else involved is a "helper".  If the helper has an appropriate [Skill](Skills.md), the actor may add +2 to the [D20 check](#the%20d20%20check).  If a helper doesn't have an applicable Skill, but one of their **passions** applies, the helper may spend a [Fortune Point](#fortune) to grant the actor a +2 bonus.  After the first helper, any subsequent helpers only add +1 to the check (with the same criteria) up to a maximum of doubling the actor's [Skill Bonus](Skills.md#skill%20ranks).

### Contested Checks
When two individuals are working against one another, a **Contested Check** is called for.  Each party performs a [D20 Check](#the%20d20%20check).  Whosoever has the highest total is the winner of the contest.  If there is a tie, and the GM determines that a tie does not make sense given the situation, both parties re-roll.

Some contests require multiple checks to resolve.  For example, a long foot race may require 3 total checks to complete.  In this case, whomever achieves the most victories is considered the overall winner.

### Passive Checks
In cases where a **Passive Check** is called for, the check is made with an assumed d20 roll of 8.  Thus, a character’s ‘Passive Perception’ check would be 8 + Wisdom Modifier.

It is helpful to have the following passive checks written down ahead of time: [Perception](Skills.md#perception), [Insight](Skills.md#insight) and each [Saving Throw](#saving%20throw).

---
## Die Adjustments
Occasionally the rules will call for a die type to be stepped up or stepped down.  Use the table below to find the current die type and move left if the die type is being reduced or right if it's being increased.

| Dice Progression |
|:----------------:|
| d2 => d3 => d4 => d5 => d6 => d8 => d10 => d12 => d16 => d20 |

- For a d2, roll 1d4 and divide the result in half, rounding up.
- For a d3, roll 1d6 and divide the result in half, rounding up.
- For a d5, roll 1d10 and divide the result in half, rounding up.
- For a d16, roll 1d4 and 1d8.  If the d4 is 1-2, add 0 to the d8 roll.  If the d4 is 3-4 add 8.

---
## Rounding
Unless stated otherwise, the common convention is to round decimal values of 0.5 or greater up to the nearest whole number.  Values less than 0.5 are rounded down to the nearest whole number.

---
## Countdown Pools
Occasionally, the rules will call for the formation of a **Countdown Pool**.  Typically this is expressed in the form of "#p#" followed by a time unit (such as 2p6 minutes).  This is a pool of dice that are rolled at every specified time increment.  Each die that comes up a ‘1’ is removed from the pool.  When all dice have been removed from the pool, whatever effect is indicated by the countdown pool completes.

### The Death Pool
One special **Countdown Pool** is the **Death Pool**.  A Death Pool is a number of 4-sided dice equal to the creature's *Constitution Modifier* plus its *Wisdom Modifier*; with a minimum pool size of 1.  This is rolled at the end of each of the creature's [Turns](Combat.md#time) and when the pool is empty, the creature expires.  Only PCs and important NPCs will have a Death Pool.  All other creatures will simply die when they reach 0 HP.

### Countdown Pool Average Number of Rolls

<!-- directives:[] -->
<div id="content">
    <table border=2>
        <thead>
            <tr style="background-color:#708090;">
                <th id="pool_size" style="text-align:center;">Pool Size</th>
                <th id="d6" style="text-align:center;">D6</th>
                <th id="d4" style="text-align:center;">D4</th>
                <th id="d3" style="text-align:center;">D3</th>
                <th id="d2" style="text-align:center;">D2</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td style="text-align:center;">1</td>
                <td style="text-align:center;">3-4</td>
                <td style="text-align:center;">1-2</td>
                <td style="text-align:center;">1-2</td>
                <td style="text-align:center;">1-2</td>
            </tr>
            <tr style="background-color:#91a3b0;">
                <td style="text-align:center;">2</td>
                <td style="text-align:center;">7-8</td>
                <td style="text-align:center;">4-5</td>
                <td style="text-align:center;">3-4</td>
                <td style="text-align:center;">2-3</td>
            </tr>
            <tr>
                <td style="text-align:center;">3</td>
                <td style="text-align:center;">9-10</td>
                <td style="text-align:center;">6-7</td>
                <td style="text-align:center;">4-5</td>
                <td style="text-align:center;">2-3</td>
            </tr>
            <tr style="background-color:#91a3b0;">
                <td style="text-align:center;">4</td>
                <td style="text-align:center;">11-12</td>
                <td style="text-align:center;">7-8</td>
                <td style="text-align:center;">5-6</td>
                <td style="text-align:center;">3-4</td>
            </tr>
            <tr>
                <td style="text-align:center;">5</td>
                <td style="text-align:center;">12-13</td>
                <td style="text-align:center;">8-9</td>
                <td style="text-align:center;">5-6</td>
                <td style="text-align:center;">3-4</td>
            </tr>
            <tr style="background-color:#91a3b0;">
                <td style="text-align:center;">6</td>
                <td style="text-align:center;">13-14</td>
                <td style="text-align:center;">8-9</td>
                <td style="text-align:center;">6-7</td>
                <td style="text-align:center;">3-4</td>
            </tr>
        </tbody>
    </table>
</div>

---
## Fortune
A measure of a character’s luck, determination or the hand of fate, **Fortune Points** may be spent in various ways to aid a character and are earned when a character’s [Passions](CharacterCreation.md#passions) affect the character in a negative way.

A character has a **Base Fortune Point** (**BFP**) score equal to their level divided by two (rounded up).  When a character starts play and each time they complete an [Extended Rest](Combat.md#extended%20rest), their **Fortune Points** are set to their **BFP** value, regardless of if they were higher or lower than this value when the rest was started.  A character’s **Max Fortune Point** (**MFP**) score is equal to their level.  If a character would earn more FPs than their MFP, the excess points are lost.

**Fortune Points** may be spent in the following ways.

<table border=2>
    <tr style="background-color:#708090;">
        <th><b>Use</b></th>
        <th><b>Effect</b></th>
    </tr>
    <tr>
        <td>Help a Friend</td>
        <td>If a friend is performing a <i>D20 Check</i> that is related to one of your <i>Passions</i>, you may spend a <b>Fortune Point</b> to take the <i>Help</i> action.</td>
    </tr>
    <tr style="background-color:#91a3b0;">
        <td>Second Chance</td>
        <td>A <b>Fortune Point</b> may be spent to re-roll a failed <i>D20 Check</i> so long as that check is in service to one of your <i>Passions</i>. Only one die may be re-rolled (thus a roll with <i>Advantage</i> or <i>Disadvantage</i> only re-rolls 1 of the two dice, not both).</td>
    </tr>
    <tr>
        <td>Lucky Situation</td>
        <td>A <b>Fortune Point</b> may be spent to use something in the environment to your benefit, or introduce a reasonable element that can be used. For example, a nearby hay stack may be used to cushion a fall off the roof of a building. This must be in service to one of your <i>Passions</i>.</td>
    </tr>
    <tr style="background-color:#91a3b0;">
        <td>Cheat Death</td>
        <td>A character who has reached 0 HP, may spend a <b>Fortune Point</b> to automatically stabilize and not need to continue rolling their <i>Death Pool</i>. However, they are still at 0 HP and <i>Unconscious</i>. This may always be done, even if not directly related to a <i>Passion</i>.</td>
    </tr>
    <tr>
        <td>Special Ability</td>
        <td>Certain <i>Traits</i> and <i>Class Abilities</i> require the expenditure of a <b>Fortune Point</b> to activate. This may always be done, even if not directly related to a <i>Passion</i>.</td>
    </tr>
</table>

---
## Names
All creatures have a common name, which they will use freely.  Supernatural creatures (including spellcasters) also have a **True Name**, which they keep secret.  Knowing a supernatural creature’s true name gives one power over it and makes one more resistant to its supernatural abilities.  Typically this is expressed via the [Advantage and Disadvantage](#advantage%20and%20disadvantage) mechanics.

---
## Tags
Most everything in the game world has one or more tags.  These are purely a game-mechanic concept and have no representation within the game world.  By themselves, tags do not have any mechanics tied to them.  However, other rules (special abilities, supernatural powers, etc.) may have effects specific to particular tags.

*For example: an [elf](species/Elf.md) character has the “humanoid” and “fae” tags.  Any ability or power referencing either “humanoid” or “fae” will affect an [elf](species/Elf.md).  However, something that only affects creatures with the “undead” tag would not affect the [elf](species/Elf.md).*

### Damage Types
Damage Types are a particular form of **Tag** that denotes the nature of the damage an attack does.  Different creatures may be [Resistant](Combat.md#resistant) or [Vulnerable](Combat.md#vulnerable) to one or more types of damage.

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
## Charisma and Reactions
A **Reaction Check** is made upon the PCs meeting an NPC or group of NPCs for the first time and how they may react is uncertain.  Unlike other [D20 Checks](#the%20d20%20check), this is not a simple pass/fail test.  Instead the D20 is rolled and the spokesperson's *Charisma Modifier* is added to the roll.  If the NPC group is inclined to be hostile, the roll is made with [Disadvantage](#advantage%20and%20disadvantage).  If they are already inclined to be friendly, the roll is made with *Advantage*.  Most groups are neutral and this will simply be a standard roll.  Compare the total rolled to the table below.

### Reaction Check Result Table
<table border=2>
    <thead>
        <tr style="background-color:#708090;">
            <th id="d20" style="text-align:left;">d20</th>
            <th id="result" style="text-align:left;">Result</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="text-align:left;">1-</td>
            <td style="text-align:left;"><strong>Hostile:</strong> Will either attack or otherwise attempt to thwart the PCs. If hostile action is not possible or obvious suicide, will attempt to flee or get help.</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">2 to 6</td>
            <td style="text-align:left;"><strong>Unfriendly:</strong> Will either attack or otherwise thwart the PCs if the NPCs have the upper hand. Otherwise will watch the PCs warily to see what they do.</td>
        </tr>
        <tr>
            <td style="text-align:left;">7 to 14</td>
            <td style="text-align:left;"><strong>Neutral:</strong> The NPCs are undecided and will keep a watch on what the PCs do before deciding on their own course of action.</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">15 to 19</td>
            <td style="text-align:left;"><strong>Indifferent:</strong> Open to friendly negotiation or simply going about one another’s business unmolested.</td>
        </tr>
        <tr>
            <td style="text-align:left;">20+</td>
            <td style="text-align:left;"><strong>Friendly:</strong> Willing to cooperate with the PCs and even provide assistance if such is not dangerous or too costly.</td>
        </tr>
    </tbody>
</table>

---
## Hazards and Challenges
### Climbing
Characters can normally climb at a rate equal to half their ground movement, assuming sufficient handholds and calm, dry conditions.  Should conditions become truly hazardous (such as rainfall, high winds or or similar) or the climb be tricky (overhangs, sparse handholds, etc), a Dexterity+[Athletics](Skills.md#athletics) Check should be made, with an appropriate [Difficulty](#difficulty).  If the check fails, the character will [fall](#falling) at the mid-point of that segment of the climb.

#### Long Climbs
For very long climbs (more than around 100 feet), multiple checks should be made (typically about one every 100 feet or so).

#### Sheer Surfaces
Very steep or sheer surfaces cannot normally be climbed without specialized climbing equipment.

### Falling
Falling from a height onto a hard surface inflicts blunt damage onto the falling creature.  The following table denotes how much damage a creature takes when falling from a given height, as well as how long that fall will take.

<table border=2>
    <thead>
        <tr style="background-color:#708090;">
            <th id="time" style="text-align:right;">Time</th>
            <th id="velocity" style="text-align:right;">Velocity</th>
            <th id="dist" style="text-align:right;">Dist</th>
            <th id="damage" style="text-align:right;">Damage</th>
            <th id="notes" style="text-align:left;">Notes</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="text-align:right;">0.40s</td>
            <td style="text-align:right;">10fps</td>
            <td style="text-align:right;">3ft</td>
            <td style="text-align:right;">1d6</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:right;">0.60s</td>
            <td style="text-align:right;">20fps</td>
            <td style="text-align:right;">6ft</td>
            <td style="text-align:right;">2d6</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr>
            <td style="text-align:right;">0.90s</td>
            <td style="text-align:right;">30fps</td>
            <td style="text-align:right;">13ft</td>
            <td style="text-align:right;">3d6</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:right;">1.20s</td>
            <td style="text-align:right;">40fps</td>
            <td style="text-align:right;">23ft</td>
            <td style="text-align:right;">4d6</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr>
            <td style="text-align:right;">1.60s</td>
            <td style="text-align:right;">50fps</td>
            <td style="text-align:right;">41ft</td>
            <td style="text-align:right;">5d6</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:right;">1.90s</td>
            <td style="text-align:right;">60fps</td>
            <td style="text-align:right;">58ft</td>
            <td style="text-align:right;">6d6</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr>
            <td style="text-align:right;">2.20s</td>
            <td style="text-align:right;">70fps</td>
            <td style="text-align:right;">77ft</td>
            <td style="text-align:right;">7d6</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:right;">2.60s</td>
            <td style="text-align:right;">80fps</td>
            <td style="text-align:right;">108ft</td>
            <td style="text-align:right;">8d6</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr>
            <td style="text-align:right;">3.00s</td>
            <td style="text-align:right;">90fps</td>
            <td style="text-align:right;">144ft</td>
            <td style="text-align:right;">9d6</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:right;">3.40s</td>
            <td style="text-align:right;">100fps</td>
            <td style="text-align:right;">185ft</td>
            <td style="text-align:right;">10d6</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr>
            <td style="text-align:right;">3.80s</td>
            <td style="text-align:right;">110fps</td>
            <td style="text-align:right;">231ft</td>
            <td style="text-align:right;">11d6</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:right;">4.30s</td>
            <td style="text-align:right;">120fps</td>
            <td style="text-align:right;">296ft</td>
            <td style="text-align:right;">12d6</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr>
            <td style="text-align:right;">4.80s</td>
            <td style="text-align:right;">130fps</td>
            <td style="text-align:right;">369ft</td>
            <td style="text-align:right;">13d6</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:right;">5.40s</td>
            <td style="text-align:right;">140fps</td>
            <td style="text-align:right;">467ft</td>
            <td style="text-align:right;">14d6</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr>
            <td style="text-align:right;">6.00s</td>
            <td style="text-align:right;">150fps</td>
            <td style="text-align:right;">576ft</td>
            <td style="text-align:right;">15d6</td>
            <td style="text-align:left;">1 Round</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:right;">7.00s</td>
            <td style="text-align:right;">160fps</td>
            <td style="text-align:right;">784ft</td>
            <td style="text-align:right;">16d6</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr>
            <td style="text-align:right;">8.20s</td>
            <td style="text-align:right;">170fps</td>
            <td style="text-align:right;">1,076ft</td>
            <td style="text-align:right;">17d6</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:right;">10.00s</td>
            <td style="text-align:right;">180fps</td>
            <td style="text-align:right;">1,600ft</td>
            <td style="text-align:right;">18d6</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr>
            <td style="text-align:right;">15.60s</td>
            <td style="text-align:right;">190fps</td>
            <td style="text-align:right;">3,894ft</td>
            <td style="text-align:right;">19d6</td>
            <td style="text-align:left;">Terminal V.</td>
        </tr>
    </tbody>
</table>

### Disease

### Poison

### Starvation
Going for more than a day without food or water incurs significant penalties.  Any character going more than a day without food will gain 1 level of [Exhaustion](Combat.md#Exhaustion) per day and they cannot recover levels of exhaustion until they get a meal.  Any character going more than a day without water will gain 1 level of Exhaustion per [Watch](RulesSynopsis.md#Time) after that first day and cannot recover any levels of exhaustion until they get water.

### Swimming
All characters can swim at half their normal ground movement rate.  In rough conditions (heavy current, rapids, inclement weather, etc), a Strength+[Athletics](Skills.md#athletics) check may be required for the character to keep their head above water.

#### Drowning
Characters failing a swim check will begin drowning.  If they had a chance to draw a breath, a character can hold their breath for a number of minutes equal to their *Constitution Modifier* (minimum of 30 seconds).  If they did not get the chance to draw a breath, halve this time.  Each round after this time passes, the character will gain 1d4 levels of [Exhaustion](Combat.md#exhaustion).

### Visibility
Adventurers frequently find themselves in dark and dim conditions, whether at night or under ground.

#### Dim Lighting/Obscurement
There are conditions in which there is some light but visibility is still restricted.  Such conditions include mists/fog, full moon nights, torches and lanterns being roughly a room away and so forth.  In these conditions sight-based checks and ranged attacks are made at *Disadvantage*.

#### Darkness
When there isn't even dim lighting (such as underground, a moonless or overcast night, and so forth), characters will find themselves in total darkness.  In this case, everyone is treated as if they had the [Blinded](Combat.md#Blinded) conditions.

#### Low-Light Vision
Some beings have eyesight better adapted to dim lighting conditions.  These characters can see in **Dim** light as if it were full daylight, except that the vision will be in black-and-white only.  They are still [Blinded](Combat.md#Blinded) by total **Darkness**.

#### Darkvision
Some creatures have true Darkvision, allowing them to not only see normally in **Dim** lighting (they can still discern color in dim lighting) they also treat full **Darkness** as normal creatures would treat dim lighting.

---
## Time
Time is broken up into three broad categories: *Combat Time*, *Exploration Time* and *Narrative Time*.  

**Combat Time** is measured in *Combat Turns* (one creature’s chance to move and act), *Rounds* (the combined Turns of all participants; approximately 10 seconds) and *Minutes* (1 minute = 6 Rounds).  

**Exploration Time** is measured in *Exploration Turns* (approximately 10 minutes), *Hours* and *Watches* (4 Hours).  

**Narrative Time** is not strictly tracked and, instead, the GM determines how much time has passed once the narration is concluded.  

*For example, a group traveling a well-known safe road from one town to the next may take a full day’s travel.  The GM should declare this as narrative time and simply inform the group that 1 day of travel has passed.  On the other hand, if the group is traveling through a dangerous wilderness where they may be ambushed by monsters or other enemies, it’s recommended that this be treated as Exploration Time tracked in either Hours or Watches as the GM deems appropriate.  Similarly, if the group is exploring a dungeon, 10 minute Exploration Turns would be called for.*

### Time Steps
Occasionally, the rules will call for the time something takes to be moved up or down one step:
- 1 Reaction
- 1 Action
- 1 Round (10 seconds)
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