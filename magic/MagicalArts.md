# The Magical Arts

# Table of Contents
- [Spellbooks](#Spellbooks)
	- [Learning New Spells](#Learning%20New%20Spells)
		- [Learning From a Mentor](#Learning%20From%20a%20Mentor)
	- [Replacing a Spellbook](#Replacing%20a%20Spellbook)
- [Magical Focus](#Magical%20Focus)
	- [Replacing a Focus](#Replacing%20a%20Focus)
	- [Inscribing Sigils](#Inscribing%20Sigils)
- [Preparing Spells](#Preparing%20Spells)
	- [Casting Unprepared Spells](#Casting%20Unprepared%20Spells)
- [The Invocation Roll](#The%20Invocation%20Roll)
	- [Quick Summary](#Quick%20Summary)
	- [The Invocation Dice Pool](#The%20Invocation%20Dice%20Pool)
		- [Exhausting Magic](#Exhausting%20Magic)
		- [Magical Focus](#Magical%20Focus)
	- [Spell Difficulty](#Spell%20Difficulty)
	- [Invocation Dice Recovery](#Invocation%20Dice%20Recovery)
	- [Magical Attacks and Saving Throws](#Magical%20Attacks%20and%20Saving%20Throws)
	- [Spell Identification](#Spell%20Identification)
- [Concentration](#Concentration)
- [Mishaps](#Mishaps)
	- [Minor Magical Mishap](#Minor%20Magical%20Mishap)
	- [Major Magical Mishap](#Major%20Magical%20Mishap)
	- [Physical Corruption](#Physical%20Corruption)
	- [Random Elements](#Random%20Elements)

## Spellbooks
Spellcasters record their [spells](magic/Spells.md) and cantrips in "spellbooks".  These do not have to be literal books, but rather may be collections of scrolls, arcane formula carved into wood or most any other device the player and GM can agree on.  The primary limitation is that the spellbook be separate from the character (arcane tattoos are more of a magical item than a spellbook).  The language in which [spells](magic/Spells.md) are written are typically a magical cipher learned from the caster's teacher and modified in their own way.  As such, deciphering someone else's spellbook can be a long and arduous process.

A typical spellbook costs 100sp and can hold up to 100 pages worth of [spells](magic/Spells.md).
### Learning New Spells
New [spells](magic/Spells.md) take hours, days or weeks to properly learn.  While learning a new spell, the mage may take part in no other form of [downtime activity](Downtime.md); all their working hours being consumed with study and preparation.

When learning a new spell, it must be recorded in the mage’s spellbook.  Each cantrip takes up half of a page, while each spell takes up a number of pages equal to its base **[Tier](Spells.md#tier)**.  For each page a spell takes up, it also takes 10 hours and 100sp worth of study and materials to properly learn and record the spell (cantrips take 5 hours and 50sp).

Once the calculated learning time has passed, the mage makes a **[Skilled Intelligence](RulesSynopsis.md#skilled%20check)** roll with a DT equal to 10 plus the spell's base [Tier](Spells.md#tier).  Failure results in the loss of all time and materials used in the attempt and the mage may not attempt to learn this spell again until they’ve gained a new level.

#### Learning From a Mentor
Spellcasters may also learn [spells](magic/Spells.md) from other casters (if they can find one willing to teach their jealously guarded secrets).  The teacher is assumed to be taking the [Help](Combat.md#Main%20Actions) action in regards to the student learning the spell.  This also halves the amount of time required to learn the spell (though the material cost remains the same).

### Replacing a Spellbook
If a spellbook is lost or destroyed, it may be recreated using the [spells](magic/Spells.md) that the spellcaster has already prepared.  Doing so requires a specially prepared [spellbook](#spellbooks) and takes the same cost in time and materials as learning each spell anew.

-[ ] Backup copies

## Magical Focus
A magical focus is a device that aids a spellcaster in channeling and controlling their magic.  This device must be easily seen, recognized and hand-held.  It also takes up 1 [inventory slot](EncumbranceAndEquipment#encumbrance).

A spellcaster may inscribe a number of known [sigils](magic/Sigils.md) into their Focus.  This allows the inscribed [sigils](magic/Sigils.md) to count as being on-hand so long as the caster has their Focus in-hand.  Additionally, and [spells](magic/Spells.md) utilizing that sigil may be cast using d8s for the Invocation Dice instead of d6s.

### Replacing a Focus
A focus may be replaced by constructing a new one which takes 1 week in a [safe haven](Combat.md#extended%20rest) and 100sp worth of materials.

### Inscribing Sigils
It takes one day plus 50sp, to inscribe a [sigil](magic/Sigils.md) into a Magical Focus.

## Preparing Spells
A spellcaster may only cast [spells](magic/Spells.md) they have prepared.  [Cantrips](magic/TierZeroSpells.md) are always prepared, so they can always be cast.  [Spells](magic/Spells.md) of [Tier 1](magic/Spells.md#tier) or higher take time to prepare.  A spellcasters may only prepare as many [spells](magic/Spells.md) as their [Skill Bonus](Glossary.md#skill%20bonus) plus their Intelligence Modifier. Preparing a spell takes 10 minutes times the spell's [Tier](magic/Spells.md#tier).  Once a spell is prepared, it remains prepared until the caster chooses to replace it with a different spell or some event causes the mage to temporarily lose the spell.

### Casting Unprepared Spells
A spellcaster, so long as they have access to their spellbook, may cast unprepared [spells](magic/Spells.md) using said spellbook.  Doing so increases the casting time of the spell [1 step](RulesSynopsis.md#time%20steps), to a minimum of 10 minutes.

*For example, a character wishing to cast [Augury](magic/TierTwoSpells.md#augury) as an unprepared spell must have their spellbook on hand.  Since the base casting time is 10 minutes, it will now take 1 hour to cast the spell in this manner.*

## The Invocation Roll

With thanks to the [Spell Dice](https://www.necropraxis.com/2013/11/01/spell-dice/) system by Necropraxis.

### Quick Summary
- Spellcasters get an **[invocation pool](#the%20invocation%20dice%20pool)** of six-sided dice based on their **Level** and **Wisdom Modifier**.
- Any number of dice may be used to cast a spell.
- **[Spell difficulty](#spell%20difficulty)** is equal to the spell’s [tier](magic/Spells.md#tier) times 3.
- Any **invocation die** that that roll a [natural](RulesSynopsis.md#natural%20results) 1 or 2 is removed from the pool (aka **expended**).
- Some expended **invocation dice** may be recovered after a **rest**.

### The Invocation Dice Pool
A spellcaster gets a pool of six-sided dice with which to cast their [spells](magic/Spells.md).  The total number of dice in the pool is based on the character’s **Class** and **Level** plus additional dice equal to their **Wisdom Modifier**.

*Example: A 5th level [Spellcaster](classes/Spellcaster.md) with a 16 Wisdom (+2 modifier) has a pool of 7d6 **Invocation Dice**.*

When casting a spell, the caster may choose to roll any number of **invocation dice** in order to try to meet or exceed the **[spell difficulty](#spell%20difficulty)**.  Any dice rolling a [natural](RulesSynopsis.md#natural%20results) ‘1’ or ‘2’ are **expended** from the pool (though still counted toward the casting result) and cannot be used again until **recovered**.

#### Exhausting Magic
If a spellcaster finds themselves in need of a quick boost of magical energy, they may add their **[Skill Bonus](Glossary.md#skill%20bonus)** to their **Invocation Roll** by gaining 1 level of [Exhaustion](Combat.md#Exhaustion).  This may be done as a [Free Action](Combat.md#free%20actions).

#### Magical Focus
While a spellcaster has their [magical focus](#magical%20focus) is in hand, and if that focus has the proper [sigils](magic/Sigils.md) carved into it, the spellcaster may roll d8s instead of d6s for their invocation dice.

*Example: A 5th level [Spellcaster](classes/Spellcaster.md) wishes to cast the "fireball spell" (aka [Arcane Eruption (fire)](magic/TierThreeSpells.md#Arcane%20Eruption)) (Tier 3), so the difficulty is 9+.  Normally, they would roll up to 5d6 to cast the spell (probably using 3 to be on the safe side).  However, if they have the Fire [sigil](Sigils.md) carved into their magical focus, they would roll d8s and thus would be reasonably safe rolling only 2 dice to cast the spell (thus reducing the chance of a [Mishap](#mishaps)).*

### Spell Difficulty
A spell’s **difficulty** is equal to 3 times the [tier](magic/Spells.md#tier) at which it is cast.  **[Cantrips](magic/TierZeroSpells.md)**, being Tier 0, are difficulty zero than thus do not need an invocation roll unless cast at a higher tier.

| Rank | Difficulty |
|:----:|:----------:|
| 0    |  0         |
| 1    |  3         |
| 2    |  6         |
| 3    |  9         |
| 4    | 12         |
| 5    | 15         |
| 6    | 18         |

*Example: A character casting [Arcane Arrow](magic/TierOneSpells.md#arcane%20arrow) at **rank** 3 must beat a spell difficulty of 9 (3x3).*

If a spell’s **difficulty** is not met, the spell is not cast.  However, the mage may choose to continue casting the spell.  This requires that the mage reserve the dice already used in casting the spell and [Concentrate](Combat.md#Concentrating) long enough to satisfy the spell’s **[casting time](magic/Spells.md#casting%20time)** again.  Once this time increment has passed, the mage may choose to roll additional **invocation dice** and add their total to the **spellcasting roll**.  In this way, more difficult [spells](magic/Spells.md) can be cast over multiple “rounds”.

*Example: The above 5th level [Spellcaster](classes/Spellcaster.md) with a 16 Wisdom is attempting to cast a ["fireball"](magic/TierThreeSpells.md#arcane%20eruption) at **Tier** 3 (difficulty 9).  They choose to be conservative and roll only 3 dice, rolling a ‘1’, '3' and ‘4’, for a total of 8.  As the total is less than the **difficulty**, the spell is not cast.  The character chooses to continue the casting. This means they are now **concentrating** and they set aside the 3 dice already rolled, leaving 4 left unallocated in their **invocation pool**.  On their next round (since the spell has a **casting time** of 1 **action**), they choose to roll one more die, getting another ‘1’.  This brings their total to 9, successfully casting the spell.  The two ‘1’s are now **expended**, and the other three committed dice are now released.  This leaves the caster with 5 dice in their **invocation pool**.  Note that no [Mishap](#Mishaps) roll is made because the two '1's occurred on two separate rolls.*

### Invocation Dice Recovery
Whenever a spellcaster completes a [Short Rest](Combat.md#Short%20Rest), they may roll a portion of their **expended** **invocation dice**.  Any of those dice that come up a 2+ are placed back into the caster’s **invocation pool**.  The number of dice that may be rolled after a short rest is equal to their **Wisdom Modifier**.

After a [Long Rest](Combat.md#Long%20Rest), the same procedure is followed with the following 2 exceptions:
- A number of dice equal to the character’s **Wisdom Modifier** are recovered without rolling.
- The caster may then roll all their remaining **expended** **invocation dice**.

After an [Extended Rest](Combat.md#Extended%20Rest), all **invocation dice** that have been **expended** are automatically recovered.

### Magical Attacks and Saving Throws
Once a spell has successfully been invoked, the mage may then need to make a **Magical Attack Roll**.  This is similar to a normal [Attack Roll](Combat.md#attacking%20an%20enemy), but uses the mage’s **Skill Bonus** and the **Ability Modifier** of the ability called out by the Art in question.  If the Magical Attack Roll is a critical hit, it allows the mage to double one numerical trait of the magical art; typically range, area, number of targets, duration or damage.  In the case of damage, treat this the same as a [critical hit](Combat.md#Critical%20Hits) from a weapon; thus it’s not strictly a doubling.

Alternatively, a spell may require the target to make a [Saving Throw](CoreRules.md#Saving%20Throws) instead of requiring a spellcaster to make an attack roll.  In this case, the Spellcaster's [Spell Save Difficulty](classes/ClassAbilities.md#spellcasting) is the target number.  If the target succeeds on their save, the effects of the spell may be reduced or even mitigated entirely (according to the spell's description).

### Spell Identification
If a mage can directly see and hear another spellcaster as they cast a spell, they may attempt a [Skilled](RulesSynopsis.md#skilled%20check) **Intelligence** check vs. the spell's **casting difficulty** in order to identify the spell being cast.  If the observing mage can only see or hear the casting mage, but not both, this check is performed at **Disadvantage**.

If the check is successful and the mage has the spell in their spellbook, they completely identify the spell and whether or not it is being [upcast](magic/Spells.md#Upcasting) and to what Tier.

If the check is successful but the mage does not have the spell in their spellbook, they will only be able to discern the following:
1. Whether or not the spell is being cast at a Tier the observing mage can cast.
2. What the spell's governing Ability is (Intelligence, Wisdom or Charisma)
3. Whether the spell is offensive, defensive or utilitarian in nature.

If the check is failed, the observing mage gains no information.

Characters without the [Sense Magic](classes/ClassAbilities.md#sense%20magic) ability may not attempt this check at all.

## Concentration
Several [spells](magic/Spells.md) require **[concentration](Combat.md#concentrating)** to maintain their effects after casting.  A caster may normally only concentrate on one thing at a time.  New actions requiring concentration supersede anything the caster is already concentrating on.  If a concentrating caster takes damage, they must pass a **[Concentration Check](CoreRules.md#concentration)** (a type of **Spirit saving throw**) vs difficulty 10 or half the damage done (whichever is higher).  Other things may also require a concentration check, such as being thrown into a river, suddenly startled, being grappled and so on.  The GM will set the difficulty of the check accordingly.  Additionally, [spells](magic/Spells.md) that take more than 1 action to cast require concentration while they are being cast.  Losing concentration causes the magical art to fail (though the declared number of invocation dice must still be rolled to see if a [mishap](#mishaps) occurs and how many are expended).

## Mishaps
If two of the dice rolled at the same time come up as [natural](RulesSynopsis.md#natural%20results) ‘1’s, this will result in a [Minor Magical Mishap](#Minor%20Magical%20Mishap), even if the spell casting is successful.  If three of the dice are natural ‘1’s, then the caster suffers a [Major Magical Mishap](#Major%20Magical%20Mishap).  If four or more dice are natural ‘1’s, then the caster suffers the effects of both a **minor** and a **major** magical mishap.

Note that some tables may wish to assume that [spells](magic/Spells.md) cast when there is no time pressure (thus the caster can take as long as they want) are assumed to be rolled a single die at a time.  As a result, no mishap can occur, though dice can still be expended as normal.

### Minor Magical Mishap
| d30   | Mishap                                                                                                                                                                                                                                                                                                |
| :-:   | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|  1    | **Uncanny Shade:** The caster’s shadow turns an unnatural {color} for a 2p4 watches.                                                                                                                                                                                                            |
|  2    | **Winter’s Caress:** All free-standing water within **[Near](Combat.md#range%20bands)** range of the caster immediately freezes.                                                                                                                                                                                                 |
|  3    | **Distension:** The caster grows 1d4 inches in height.                                                                                                                                                                                                                                                |
|  4    | **Dilation:** The caster shrinks 1d4 inches in height.                                                                                                                                                                                                                                                |
|  5    | **Witch Hives:** The caster is covered in an itchy red rash that lasts 4p4 **[Exploration Turns](RulesSynopsis.md#time)**. While this rash lasts, the caster has **Disadvantage** on all DEX and **Concentration** checks.                                                                                               |
|  6    | **Tinted:** The caster’s skin turns an unnatural {color}. This can be cured by a Remove Curse ritual.                                                                                                                                                                                                |
|  7    | **Witch Eye:** An eye appears in the middle of the caster’s {body part}. It does not allow them to see any better. The eye remains for 4p4 Hours.                                                                                                                                               |
|  8    | **Elemental Summoning:** An {elemental} creature chosen by the GM appears within 5 feet of the caster. Make a [Reaction Check](CoreRules.md#Charisma%20and%20Reactions) to determine its attitude toward the caster. The creature will disappear after 3p4 rounds.                                 |
|  9    | **Fowl Beard:** The caster grows a long beard of {color} feathers that remains until the next time they sneeze.                                                                                                                                                                                       |
| 10    | **Vanishing:** The caster is transported to a mysterious pocket dimension until the end of their next turn, at which time they return to the space they previously occupied or the nearest unoccupied space.                                                                                          |
| 11    | **Time Skip:** The caster ages 1d4 years.                                                                                                                                                                                                                                                             |
| 12    | **Reverse Time:** The caster’s ages -1d4 years.                                                                                                                                                                                                                                                       |
| 13    | **Fae Summoning:** 1d6 {fae} creatures appear in unoccupied spaces within **[Near](Combat.md#range%20bands)** distance of the caster. Make a [Reaction Check](CoreRules.md#Charisma%20and%20Reactions) to determine their attitude toward the caster. They vanish after 2p4 minutes.                                          |
| 14    | **Levitation:** The caster levitates 1d10 feet up into the air. This effect lasts 4p4 [rounds](Combat.md#time). At the start of each of the caster’s [turns](Combat.md#time), their elevation changes randomly by 2d6-7 feet.  Running into a surface may hurt and embarrass, but no actual HP damage will be done. |
| 15    | **Beastly Presence:** A {beast} appears within 5 feet of the caster. Make a [Reaction Check](CoreRules.md#Charisma%20and%20Reactions) to determine its attitude toward the caster. It disappears after 3p4 rounds.                                                                                 |
| 16    | **Depilation:** The caster’s hair falls out but grows back within 1p4 days.                                                                                                                                                                                                                     |
| 17    | **Uncontrollable Shout:** The caster must shout whenever they speak. This condition lasts for 3p6 minutes.                                                                                                                                                                                      |
| 18    | **Obscuring Mist:** The effect of a tier 2 **[Gather Mists](magic/TierOneSpells#Gather%20Mist/Shadows)** spell is centered on the caster. |
| 19    | **Wyrdlight:** The caster suffers the effects of a {color} *[Faerie Fire](magic/TierOneSpells.md#faerie%20fire)* spell for 2p6 Turns.                                                                                                                                                                                                   |
| 20    | **Wyrdling Rain:** It’s not water. The caster inadvertently causes a torrential downpour that lasts for 2p4 minutes. Roll 1d6 to determine the substance of the downpour.<br/>1 – flower petals / 2 - garden snails / 3 - cow dung / 4 - rotten vegetables / 5 - small stones / 6 - fish        |
| 21    | **Embiggen:** The caster grows 1 size category. This lasts for 3p4 minutes.                                                                                                                                                                                                                     |
| 22    | **Shrink:** The caster shrinks 1 size category. This lasts for 3p4 minutes.                                                                                                                                                                                                                     |
| 23    | **Music From Beyond:** The caster is surrounded by faint, ethereal music for the next 3p4 minutes.                                                                                                                                                                                                         |
| 24-25 | **Witch Sign:** All {1d3: milk/wine/food} within **[near](Combat.md#range%20bands)** range of the caster immediately spoils.                                                                                                                                                                                                                       |
| 26    | **Rupture:** The caster’s nose begins to bleed and continues doing so until they pass a **[Difficulty](RulesSynopsis.md#Difficulty%20Targets) 15** **[Hardiness Save](CoreRules.md#saving%20throws)**. They can test at the start of each of their [turns](Combat.md#time). They do not take any actual damage, but are at **Disadvantage** on all smell **[Perception checks](CoreRules.md#perception)** until the bleeding stops. |
| 27    | **Breath of Chaos:** A cold and unnatural wind blows through the area for 4p4 [Rounds](Combat.md#time).                                                                                                                                                                                                                                |
| 28    | **Horripilation:** All the caster’s hair stands on end. This effect lasts 4p4 **[exploration turns](RulesSynopsis.md#time)**.                                                                                                                                                                                            |
| 29    | **Haunted:** Ghostly voices fill the air for the next 4p4 minutes. |
| 30    | **Worse Than Expected:** Roll on the **Major Magical Mishap** table. |

### Major Magical Mishap
|  d30  | Mishap                                                                                                                                                                                                                                                                                     |
| :---: | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|   1   | **Fiery Blast:** The caster becomes the center 20 ft radius explosion doing 4d6 fire damage to all in the affected area.  Everyone in the area may make an **[Evasion Save](CoreRules.md#saving%20throws)** vs **Diff 15** (the caster automatically fails this save) to take half damage. |
|   3   | **Magical Vulnerability:** The caster has **[Vulnerability](Combat.md#vulnerability)** to magical damage for 2p4 [Rounds](Combat.md#time). |
|   4   | **Mage Rot:** The caster is cursed with *Mummy Rot*. |
|   5   | **Muted:** Each time the caster tries to speak, {color} bubbles come from their mouth.  The caster’s words are heard as they pop.  This effect has a 4p6 [round](Combat.md#time) duration.  While in effect, spell difficulty is doubled. |
|   6   | **Intoxicating Power:** The caster becomes [Intoxicated](Combat.md#Intoxicated) as if drunk on alcohol.  This effect lasts 2p4 hours. |
|   7   | **Paranoia:** The caster becomes [Frightened](Combat.md#Frightened) of the nearest creature until the end of their next [turn](Combat.md#time). |
|   8   | **Aspect Alteration:** The caster must make a **[Hardiness Save](CoreRules.md#saving%20throws)** vs **diff 15** or be turned into an {animal}.  If transformed, they may repeat the save once each minute until they succeed and change back.  They automatically revert to their true form if reduced to 0 HP. |
|   9   | **Susceptible:** The caster and all creatures within 30 feet gain **[vulnerability](Combat.md#vulnerability)** to {damage type} for the next minute. |
|  10   | **Mindblast:** 1d4+1 of the caster's **Invocation Dice** are immediately **expended**. |
|  11   | **Silenced:** The caster loses their voice for 3p4 minutes. |
|  12   | **Overload:** The caster is overwhelmed by magical energy and has the [Stunned](Combat.md#Stunned) condition until they pass a **diff 15** **[Hardiness Save](CoreRules.md#saving%20throws)**.  They may roll the save at the end of each of their [turns](Combat.md#time) excepting the turn they gained this condition. |
|  13   | **Outside Interference:**  The caster is attacked by 2d6 HD of {aberrations} (minimum 1 creature).  They appear within 1d6 times 10 feet of the caster in a random direction.  They continue their assault for 4p4 [rounds](Combat.md#time) unless defeated. |
|  14   | **Etheric Shock:** The caster takes 3d8 lightning damage. |
| 15-20 | **Enfeeblement:** Magical energy wracks the caster’s body, draining {ability} by 1d6 points.  This effect lasts 4p4 minutes. |
|  21   | **Assault From Beyond:** The winds of magic lash the caster and they must roll 1d10+10 on the [Lingering Injury](Combat.md#Lingering%20Injuries) table. |
|  22   | **The Hounds of Hell:** The caster is attacked by 2d6 HD of {fiends} (minimum 1 creature).  They appear within 1d6 times 10 feet of the caster in a random direction.  They remain for 4p4 [rounds](Combat.md#time) or until defeated. |
| 23-27 | **Physical Corruption:**  Roll on the [Physical Corruption](#Physical%20Corruption) table.  This is a permanent curse. |
| 28-30 | **Miscast:**  The caster inadvertently channels the wrong magical energies. Randomly determine a different magical art of the same type and tier. Have the mage reroll their **invocation roll** for the new art. If the check fails, nothing happens. If it is a success, follow the results. |

### Physical Corruption
The afflictions on this table never heal naturally.  Only the intervention of strong healing magic or curse removal can remedy these afflictions.

| d10 | Corruption                                                                                                                                                                                                                                                                                                                                                                                                                              |
| :-: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|  1  | **Boils:** Character develops horrid pustules on his face. These pustules do not heal naturally and impose a -1 penalty all **Charisma** checks.                                                                                                                                                                                                                                                                                        |
|  2  | **The Melting:** Character’s skin on {body part} appears to melt. Like wax, it flows and reforms into odd puddles and shapes. This is an ongoing, constant motion that itches constantly and repulses others.                                                                                                                                                                                                                          |
|  3  | **Lopsided:** One of the character’s {body part} grows 1d3”. Character now moves awkwardly.                                                                                                                                                                                                                                                                                                                                             |
|  4  | **Evil Eye:** Roll 1d4:<br/>1 – eyes glow with unearthly {color}<br/>2 – eyes turn pure white and gain light sensitivity (**disadvantage** on all sight-based [perception rolls](CoreRules.md#perception) and ranged attack rolls in bright light) but also gain **[darkvision](CoreRules.md#darkvision)** 60 ft<br/>3 – eyes turn pure black<br/>4 – eyes become large and unblinking, like a fish.                                                                                          |
|  5  | **Weeping Sores:** Character develops painful lesions on his chest and legs and open sores on his hands and feet that do  not heal naturally.                                                                                                                                                                                                                                                                                            |
|  6  | **Mutated Auris:** Roll 1d6:<br/>1 – ears become long and pointed<br/>2 – ears fall off (character still hears normally)<br/>3 – ears  enlarge and look like an elephant’s<br/>4 – ears elongate and look like a donkey’s (character also gains braying laugh)<br/>5 – ears shrivel and fold back<br/>6 – ears elongate, droop and become {color} furred like a lop-eared rabbit                                                        |
|  7  | **Chills:** Character shakes and their teeth chatter constantly.  They have **disadvantage** on stealth checks and gain **[vulnerability](Combat.md#vulnerability)** to cold damage.                                                                                                                                                                                                                                                                               |
|  8  | **Disfigurement:** Character’s appearance is permanently disfigured according to the magic that was summoned. If  fire magic was used, his eyebrows are scorched and his skin glows red; if cold magic was used, his skin is pasty white and his lips are blue. If necromantic magic was used, his appearance grows gaunt and he permanently loses 5 pounds.  Feel free to work with the GM to come up with other, comparable, effects |
|  9  | **Mutatiopillation:** Character’s hair is suffused with dark energy. Roll 1d4:<br/>1 – hair changes to a random unnatural {color}<br/>2 – hair constantly twists and writhes<br/>3 – hair falls out completely<br/>4 – hair sticks straight up.                                                                                                                                                                                         |
| 10  | **Two-Faced:** A duplicate of the character’s face grows on his back. It looks just like his normal face. The eyes, nose, and mouth can be operated independently.                                                                                                                                                                                                                                                                      |

### Random Elements
Whenever a Mishap has a result in curly braces, {}, roll on the below table.

| 1d6 | Ability | Animal   | Body Part | Color  | Creature Type | Damage Type | Aberration         | Beast           | Elemental     | Fey        | Fiend         | Undead   |
|:---:|:-------:|:--------:|:---------:|:------:|:-------------:|:-----------:|:------------------:|:---------------:|:-------------:|:----------:|:-------------:|:--------:|
|   1 | STR     | Sheep    | Face      | Red    | Elemental     | Piercing    | Gauth              | Snake, Giant    | Gargoyle      | Redcap     | Hell Hound    | Ghoul    |
|   2 | DEX     | Toad     | Arms      | Yellow | Fey           | Slashing    | Gibbering Mouther  | Dire Wolf       | Mephit, Dust  | Pixie      | Babau         | Mummy    |
|   3 | CON     | Squirrel | Legs      | Blue   | Fiend         | Blunt       | Intellect Devourer | Scorpion, Giant | Mephit, Ice   | Unicorn    | Barghest      | Shadow   |
|   4 | INT     | Rabbit   | Torso     | Green  | Undead        | Fire        | Grell              | Spider, Giant   | Mephit, Magma | Harpy      | Bearded Devil | Skeleton |
|   5 | WIS     | Sparrow  | Hands     | Orange | Aberration    | Cold        | Nothic             | Stirge          | Fire Snake    | Blink Dog  | Imp           | Spectre  | 
|   6 | CHA     | Mouse    | Feet      | Purple | Beast         | Lightning   | Star Spawn Mangler | Rat, Giant      | Sala- mander  | Yeth Hound | Maw Demon     | Zombie   |  
