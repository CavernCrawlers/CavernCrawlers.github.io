# Combat
- [Time](#time)
- [Surprise](#Surprise)
	- [Ambush](#Ambush)
- [Initiative](#Initiative)
- [Actions](#Actions)
	- [Main Actions](#Main%20Actions)
	- [Move Actions](#Move%20Actions)
	- [Free Actions](#Free%20Actions)
	- [Reactions](#Reactions)
- [Attacking an Enemy](#Attacking%20an%20Enemy)
	- [Ranged Attacks](#Ranged%20Attacks)
		- [Cover](#Cover)
	- [Magical Attacks](#Magical%20Attacks)
	- [Fighting with Two Weapons](#Fighting%20with%20Two%20Weapons)
	- [Shields Shall be Splintered and Helmets Sundered](#Shields%20Shall%20be%20Splintered%20and%20Helmets%20Sundered)
	- [Damage](#Damage)
		- [What are Hit Points?](#What%20are%20Hit%20Points?)
		- [Critical Hits](#Critical%20Hits)
		- [Death and Dying](#Death%20and%20Dying)
		- [Lingering Injuries](#Lingering%20Injuries)
		- [ ] Resistance
		- [ ] Immunity
		- [ ] Vulnerability
- [Combat Maneuvers](#Combat%20Maneuvers)
	- [Combat Maneuver Examples:](#Combat%20Maneuver%20Examples:)
		- [Battle Cry](#Battle%20Cry)
		- [Blind*](#Blind*)
		- [Disarm](#Disarm)
		- [Impair*](#Impair*)
		- [Juke*](#Juke*)
		- [Shove*](#Shove*)
		- [Rally](#Rally)
		- [Trip*](#Trip*)
		- [Other*](#Other*)
- [Conditions](#Conditions)
	- [Blinded](#Blinded)
	- [Charmed](#Charmed)
	- [Concentrating](#Concentrating)
	- [Deafened](#Deafened)
	- [Exhausted](#Exhausted)
	- [Fatigued](#Fatigued)
	- [Frightened](#Frightened)
	- [Grappled](#Grappled)
	- [Incapacitated](#Incapacitated)
	- [Intoxicated](#Intoxicated)
	- [Invisible](#Invisible)
	- [Paralyzed](#Paralyzed)
	- [Petrified](#Petrified)
	- [Poisoned](#Poisoned)
	- [Prone](#Prone)
	- [Restrained](#Restrained)
	- [Stunned](#Stunned)
	- [Unconscious](#Unconcious)
- [Exhaustion](#Exhaustion)
- [Healing and Recovery](#Healing%20and%20Recovery)
	- [Short Rest](#Short%20Rest)
	- [Long Rest](#Long%20Rest)
	- [Extended Rest](#Extended%20Rest)
	- [Medical Care](#Medical%20Care)

## Time
[Time](CoreRules.md#time) in combat (and other action scenes) is tracked in relatively strict and discrete game units called **Combat Turns**, **Rounds** and **Minutes**.

A **Combat Turn** is an individual creature’s opportunity to act.  All creatures' Combat Turns are executed in descending order of [Initiative](#initiative) with tied Initiative results acting simultaneously.

A **Round** is the collection of all the Combat Turns of all the creature’s involved in the scene.  This takes up approximately 6 seconds.

A **Minute** is just that, one minute.  A minute is made up of 10 Rounds.

## Surprise
The potential for surprise exists when one or more sides are unaware of the other(s).  The members of each side make individual Wisdom+[Perception](Skills.md#perception) checks vs a difficulty of 9 (see below for Ambushes).  During the first round of combat (known as the *Surprise Round*), those who passed their perception check take their *Combat Turns* as normal.  Those who failed their perception do not get to act during the *Surprise Round*.  If everyone is unaware, they all simply stand and stare at each other for the *Surprise Round* while they both recover from surprise.  

### Ambush
If one side has advance warning of an encounter, they may attempt an *Ambush*.  In this case, the ambushing group rolls a Dexterity+[Stealth](Skills.md#stealth) check using the character with the worst modifier (counting *Disadvantage* as -4 and *Advantage* as +4 for this comparison).  This sets the difficulty of the Wisdom+[Perception](Skills.md#perception) check of the unaware side.  During the *Surprise Round*, all of the ambushers can act as normal as can any of the opposition who pass their perception check. An ambush may also provoke a [Morale](HirelingsAndAllies.md#morale) check for undisciplined targets if the GM so determines.

After the *Surprise Round*, subsequent *Rounds* proceed as normal.

## Initiative
Each participant in a combat will have an Initiative score.
- A Player Character's *Base Initiative* is equal to their *Dexterity Score* plus a modifier based on their [Class](classes/Classes.md) and [Level](ExperienceAndLevels.md).
- NPCs will have a static *Initiative* score given in their write-up.
- At the beginning of a Combat Encounter, all PCs roll 1d6 plus their *Base Initiative*.
- The highest total *Initiative* acts first in the round.  
- Play then proceeds clockwise around the table.
- When it is the GMs turn to act, all GM-controlled creatures (characters and monsters) get to act in an order decided by the GM.
- Ties
	- If there is a tie for the highest initiative, PCs will act before NPCs.  
	- If two or more PCs are tied for the highest, they determine who acts first between them.

## Actions
There are four categories of action that may be taken during a creature’s *Combat Turn*: [Main Actions](#main%20actions), [Move Actions](#move%20actions), [Free Actions](#free%20actions) and [Reactions](#reactions).

### Main Actions
Main Actions are those that will take up a majority of a creature’s time and attention during a turn.  This includes such actions as [Attacking](#attacking%20an%20enemy), [Casting a Spell](magic/MagicalArts.md), most [ability checks](CoreRules.md#ability%20check), applying [first aid](Skills.md#healing) and other such complex or lengthy endeavors.  Each participant gets one *Main Action* on their *Turn*.

Following is a list of commonly used Main Actions.  This is not a complete list, just those that come up frequently during action scenes.
- **Attack:** Make one melee or ranged [attack](#attacking%20an%20enemy) with a weapon or multiple attacks if you have a feature allowing you more than one attack per attack action.
- **Cast:**  [Cast a spell](MagicalArts.md).  (Some may be cast as reactions.)
- **Command:** The character chooses to make themselves conspicuous to the enemy and give direction to their comrades.  The commander makes a Difficulty 12 Charisma+[Persuasion](Skills.md#persuasion) check and on a success, all allies that can see and hear the commander gain +2 to hit until the start of the commander’s next *Combat Turn*.  Character’s may only benefit from one instance of the *Command* action at a time.  While giving commands, the character is distracted and anyone attacking the commanding character does so with *Advantage*.
- **Dash:** Take an extra [Move Action](#move%20actions).
- **Defend:**  A *Defending* character gains +2 to *AC* and *Evasion* saving throws until the start of their next *Combat Turn*.
- **Escape:**  *Escape* a grapple by winning an opposed {Strength or Dexterity}+[Athletics](Skills.md#athletics) check against the grappler.
- **Help:** Assist another creature within [Close](#range%20bands) range in performing an action.  If the action aligns with one of your [Skills](Skills.md), the acting creature gains +2 to their action.  If the action doesn't align with one of your *Skills*, you can still *Help* if the action is in service to one of your [Passions](CharacterCreation.md#passions), but you must pay 1 [Fortune Point](CoreRules.md#fortune) to render assistance.
- **Prepare:**  Choose a *Main Action* you will take in response to a set trigger.  Taking the triggered action uses up your [Reaction](#reactions).  Preparing a spell or cantrip requires [Concentration](Conditions.md#concentrating).
- **Protect:** Choose an ally within [Close](#range%20bands) to defend.  The protecting character gains +2 to their *AC*.  If an enemy chooses to attack the protected character, the protecting character may make an [Reflex Attack](#reactions) against the attacker.  Additionally, if the protected character is hit, the protecting character may choose to take the hit for them.
- **Overrun:** Move through an opponent’s space once by winning an opposed Strength+[Athletics](Skills.md#athletics) check.  You have *Advantage* on this check if you are at least one [Size Category](Beastiary.md#size) larger than your opponent.  You have *Disadvantage* if you are at least one size category smaller.  If you win, you move through the target creatures space without provoking a [Reflex Attack](#reactions).  The victim must make an *Evasion Save* vs your *Athletics* check or be knocked [Prone](Conditions.md#prone).
- **Ready an Item:** Move an item from your *Stowed* [inventory](EncumbranceAndEquipment.md#encumbrance) to your *Readied* inventory or vice versa.
- **Withdraw:** Your movement during your current *Combat Turn* will not provoke any [Reflex Attacks](#reactions).

### Move Actions
A standard *Move Action* allows a creature to move up to its movement rate.  Any form of movement (such as climbing, swimming, leaping or flying) is covered here.  Each creature gets one dedicated *Move Action* per *Combat Turn*.  Additionally, the *Dash* [Main Action](#main%20actions) may be used to perform a second *Move Action* in lieu of any other main actions.
- **Move:** Move up to your character’s movement rate using one of their available movement modes.
- **Stand Up:** Getting up from [Prone](Conditions.md#prone) uses up half of your movement.
- **Leap, Horizontal:** A creature may, with a running start, leap horizontally a number of feet equal to its *Strength Score* without requiring a roll.  Without a running start, halve this distance.  For greater distances, a Strength+[Athletics](Skills.md#athletics) check must be made with a *Difficulty* equal to 10 plus the number of additional feet to be crossed.  The total leap distance may not exceed the creature’s total movement.  A horizontal leap may cross any obstacle no higher than the creature’s *Strength Modifier* in feet (with a minimum of 1 foot).
- **Leap, Vertical:** A creature may leap a number of vertical feet equal to its *Strength Modifier* without requiring a roll (with a minimum of 1 foot).  Higher leaps require a Strength+[Athletics](Skills.md#athletics) check with a *Difficulty* equal to 15 plus 2 per additional foot.  The total leap height may not exceed double the creature’s *Strength Modifier*.  A vertical leap may not cross a horizontal distance greater than the creature’s *Reach*.
- **Swim:** A creature may swim at half its ground movement rate.  Swimming in calm conditions or with the current does not require a roll.  Other conditions will require a Strength+[Athletics](Skills.md#athletics) roll to successfully make progress.
- **Fly:** A creature cannot fly unless it has a defined flying movement rate.  Flying creatures ignore any terrain not at the same elevation.  Gaining altitude requires double the normal amount of movement, but lowering altitude only requires half.  Wind currents may also impact flying speed.
- **Burrow:** A creature cannot burrow unless it has a defined burrowing movement rate.  Burrowing creatures ignore all surface terrain, but different ground material compositions may impact their movement rate.  Digging deeper or shallower costs the normal amount of movement.
- **Teleportation:** Teleportation ignores all movement barriers and restrictions except those in the ending location.

### Free Actions
**Free Actions** are those minor actions that take virtually no time (such as dropping a held item, falling prone, shouting a warning, etc).  A creature may take as many free actions during their *Combat Turn* as the GM will allow.  Some Free Actions (such as speech) may be taken out of normal turn order at the GM’s discretion.

### Reactions
*Reactions* are sudden reflex actions that may be taken outside of the normal [Initiative](#initiative) order.  Each creature gets one *Reaction* per *Round*.
- **Cast:** [Cast a spell](MagicalArts.md) if the description states that it can be cast as a *Reaction*.
- **Reflex Attack:** Make a single [Attack](#attacking%20an%20enemy) (cannot be used with extra attacks) against a creature performing a reactable action.  What is reactable is typically up to the GM, but one of the most common would be a creature attempting to move out of your [Reach](EncumbranceAndEquipment.md#weapon%20properties) without first taking the [Withdraw](#main%20actions) action.
- **Trigger a Prepared Action:** If the set trigger occurs, take the [prepared action](#main%20actions).

## Attacking an Enemy
Attacking an enemy requires making a successful [Attack Roll](CoreRules.md#Attack%20Roll) vs the target's *AC*.

### Melee Attacks
Melee attacks may only be made against targets within [Close](#range%20bands) range, or within the [Reach](EncumbranceAndEquipment.md#weapon%20properties) of your melee weapon.

### Ranged Attacks
Attacks made at *Far* range have *Disadvantage* on the attack roll.

Ranged weapons (including [spells](magic/Spells.md)) with a max range of *Far* or greater, will attack at *Disadvantage* if used within *Close* range.

#### Range Bands
- **(C)lose**: 0-5 feet - Weapons with a range of *Far* have *Disadvantage* at this range.
- **(N)ear**: 6-30 feet
- **(F)ar**: 31-150 feet - Attacks made at this range have *Disadvantage* unless the character has the [Archer](classes/Knacks.md#archer) knack.
- **(S)ight**: Within Line of Sight (*LoS*).  Only siege weapons and magic attack at this range.
- **(D)istant**: Beyond perception.  Only magic may attack at this range.

#### Cover
There are two types of cover to be concerned with.  *Hard Cover* is an object or piece of terrain capable of physically stopping the attack (such as a stone wall or wooden palisade).  *Soft Cover* simply obscures the target, but will not physically stop the attack (such as fog, brush or shadows).

<table border=2>
    <thead>
        <tr style="background-color:#708090;">
            <th id="type" style="text-align:left;">Type</th>
            <th id="coverage" style="text-align:center;">Coverage</th>
            <th id="modifier" style="text-align:left;">Modifier</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="text-align:left;">Hard</td>
            <td style="text-align:center;">100%</td>
            <td style="text-align:left;">Attack is Impossible</td>
        </tr>
        <tr>
            <td style="text-align:left;">Hard</td>
            <td style="text-align:center;">51-99%</td>
            <td style="text-align:left;">+5 to target's AC</td>
        </tr>
        <tr>
            <td style="text-align:left;">Hard</td>
            <td style="text-align:center;">26-50%</td>
            <td style="text-align:left;">+2 to target's AC</td>
        </tr>
        <tr>
            <td style="text-align:left;">Hard</td>
            <td style="text-align:center;">&lt;=25%</td>
            <td style="text-align:left;">no modifier</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Soft</td>
            <td style="text-align:center;">51-100%</td>
            <td style="text-align:left;">+2 to target's AC</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Soft</td>
            <td style="text-align:center;">&lt;=50%</td>
            <td style="text-align:left;">no modifier</td>
        </tr>
    </tbody>
</table>

#### Firing Into Melee
If two or more combatants are engaged at *Close* [range](#range%20bands), they are considered to be in melee.  If a ranged attack is made against someone in melee, they are counted as having 50% [hard cover](#cover) and if the attack misses by 2 or less, one of the other creatures in melee with the target creature will be hit at random.

### Magical Attacks
Magical attacks follow the same rules as other attacks, but use one of the caster's [Mental](Glossary.md#mental%20ability%20scores) *Ability Modifiers* instead of *Strength* or *Dexterity*.  See [Magical Attacks](magic/MagicalArts.md#magical%20attacks%20and%20saving%20throws) under the *Magical Arts* document for further details.

### Fighting with Two Weapons
In order to wield 2 weapons, the weapon in the character’s primary hand must be a [Light](EncumbranceAndEquipment.md#weight) or *Medium* one-handed weapon, and the weapon in their off-hand must be a *Light* one-handed weapon.

A character wielding two weapons has the option of using their off-hand weapon *Offensively* or *Defensively*.  This choice is made at the beginning of the character’s *Combat Turn*.  If the weapon is being used *offensively*, the character gains a +1 to hit bonus and may choose to strike with either weapon (not both).  If the weapon is being used *defensively*, the character gains a +1 AC bonus and may only attack with the weapon in their primary hand.

Under no circumstances is a character allowed to attack with both weapons at the same time.  However, if a character has multiple attacks per *Combat Turn*, then they may choose which weapon to strike with each time they make an attack (subject to the above rules).

See the [Off-Hand Proficiency Trait](Traits.md#Off-Hand%20Proficiency) for additional rules.

### Shields Shall be Splintered and Helmets Sundered
Any time a character takes a hit in combat from a *Direct Attack* (not an *Area of Effect*), before the damage dice are rolled, they may choose to sacrifice their shield (assuming they are wielding one) or helmet (again assuming they are wearing one) to cancel the hit.  A buckler or helmet sacrificed is destroyed.  A shield sacrificed is treated as a buckler until it is either repaired or destroyed.

Magical shields, bucklers and helmets are not immediately sacrificed but lose one of their magical traits or have any magical “pluses” reduced by 1.  Once all magical traits and pluses are gone, the item is treated as normal.

Shields, bucklers and helmets may be repaired by a skilled [Blacksmith](Skills.md#profession).  The *Difficulty* of the check is 15 and will restore a buckler or helmet to functional or return a damaged shield to normal.  If the roll is failed, the item is permanently destroyed.  Magical items may require re-enchantment.

### Damage
#### What are Hit Points?
Hit Points represent cuts, scrapes, bruises and other minor injuries one can take from dangerous physical activity (such as combat).  It does not represent serious injuries (such as blood loss, concussion or the like).  Serious injury only occurs if a player character takes a *Critical Hit* or is dropped to [0 HP](#death%20and%20dying) or less (see the [Lingering Injuries](#lingering%20injuries) rules).  As a result, HPs heal relatively quickly.

#### Resistance
If a target is **Resistant** to the [type of damage](CoreRules.md#damage%20types) being done, it takes only half the damage (rounded down), but still takes a minimum of 1.  Likewise, if a target is **Resistant** to a [Condition](Conditions.md) being inflicted, that target gains *Advantage* on any *Saving Throws* to resist that *Condition*.

#### Immunity
If a target is **Immune** to the [type of damage](CoreRules.md#damage%20types) being done, or the [Condition](Conditions.md) being inflicted, it takes no damage and ignores the *Condition*.

#### Vulnerability
If a target is **Vulnerable** to the [type of damage](CoreRules.md#damage%20types) being done, it takes **double** the total damage rolled.  Likewise, if a target is **Vulnerable** to a [Condition](Conditions.md) being inflicted, that target suffers *Disadvantage* on any *Saving Throws* to resist that *Condition*.

#### Critical Hits
If the attack roll **exceeds** the target’s *Armor Class* by at least 1 and is a [Natural 20](CoreRules.md#natural%20roll), it is a *Critical Hit*.  When a PC receives a *Critical Hit*, they take that attack's **max damage** and may also take a [Lingering Injury](#Lingering%20Injuries).  When a PC performs a *Critical Hit*, they do their normal damage, plus the **max damage** of their weapon's damage dice.  _For example, if an attack does 1d8 + 2 damage normally, a critical hit will do 1d8 + 2 + 8.  If the attack is made by a [Rogue](Rogue.md) using their [Sneak Attack](ClassAbilities.md#sneak%20attack) ability, the Sneak Attack dice do **not** get doubled._

#### Death and Dying
As soon as a PC or important NPC drops to 0 HP, they fall [Unconscious](#unconscious).  HP are never reduced below zero.  Normal NPCs immediately die upon reaching 0 HP.

Next, form a d4 [Countdown Pool](CoreRules.md#Countdown%20Pools) equal to their *Constitution Modifier* + *Wisdom Modifier* (minimum of 1).  This [Death Pool](CoreRules.md#the%20death%20pool) is rolled at the end of each of the character’s *Combat Turns*.  Once the *Death Pool* is emptied, the character dies.  Taking a hit while dying automatically removes 1 die from the pool in addition to the normal damage.  Taking a [Critical Hit](#critical%20hits) removes 2 dice.

A character who is dying may be saved by another character attempting to *Stabilize* them.  This is done with a Wisdom+[Healing](Skills.md#healing) check vs *Difficulty* 12 (15 if done in the middle of combat).  On a success, the character is stabilized (stops rolling their [Death Pool](CoreRules.md#the%20death%20pool)).  On a [Critical Success](CoreRules.md#critical%20results), the patient is *Stabilized*, regains consciousness and rolls 1 *Hit Die* to determine their current HP.  Any healing spell *Stabilizes* a dying creature as if a *Critical Success* were rolled on the *Healing* check.

Once *Unconscious*, the character cannot be revived until they are healed back to at least 1 HP.

When an *Unconscious* character is revived, they must check for a [Lingering Injury](#Lingering%20Injuries).

#### Lingering Injuries
When a player character receives a [Critical Hit](#critical%20hit) or is reduced to [0 Hit Points](#death%20and%20dying), there is a chance they will receive a *Lingering Injury*.  

For a *Critical Hit*, the character must make a *Constitution check* vs *Difficulty* 12 or half the damage taken, whichever is higher.  On a success, no Lingering Injury occurs.  On a failure, the character rolls on the [Lingering Injury Table](#lingering%20injury%20jable) (at *Disadvantage* if their total damage exceeds the character’s *Constitution score*).

When an [Unconscious](#unconsious) character is revived, they must make a *Constitution check* vs *Difficulty* 15.  On a success, no *Lingering Injury* occurs.  On a failure, the character rolls on the [Lingering Injury Table](#lingering%20injury%20table).

##### Lingering Injury Table
<table>
    <thead>
        <tr style="background-color:#708090;">
            <th id="d20" style="text-align:center;">d20</th>
            <th id="injury" style="text-align:left;">Injury</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;"><b>Amputation:</b> Roll 1d6 and consult the table below. This never heals back naturally and can only be healed by regeneration magic.<br/>1-2: <b>Eye</b> – You have <i>Disadvantage</i> on all sight-based perception checks and ranged attacks. If both eyes are lost, permanently gain the <i>Blinded</i> condition.<br/>3-4: <b>Arm/Hand</b> – You can no longer hold anything in the amputated hand/arm.<br/>5-6: <b>Leg/Foot</b> – Your ground speed is halved and you cannot take the <i>Dash</i> action. You have <i>disadvantage</i> on <i>Evasion</i> saves and lose your DEX bonus to AC (negative DEX is still counted).</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:center;">2</td>
            <td style="text-align:left;"><b>Concussion:</b> Make a Diff 15 <i>Hardiness</i> save after each action in combat (or other physically strenuous activity). On a failure, suffer the <i>Stunned</i> condition until the end of your next <i>Combat Turn</i>. Heals naturally on a Diff 15 CON check after a <i>Long Rest</i>, or by the application of appropriate healing magic.</td>
        </tr>
        <tr>
            <td style="text-align:center;">3</td>
            <td style="text-align:left;"><b>Internal Bleeding:</b> Immediately lose 1d6 CON. If CON has been reduced to 0 or less, die immediately. Heals back at the rate of 1 CON per <i>Long Rest</i>.</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:center;">4-8</td>
            <td style="text-align:left;"><b>Broken Ribs:</b> Make a Diff 15 <i>Hardiness</i> save after each action in combat (or other physically strenuous activity). On a failure, gain 1 level of <i>Exhaustion</i>. Heals naturally on a Diff 15 CON check after a <i>Long Rest</i>, or by the application of appropriate healing magic.</td>
        </tr>
        <tr>
            <td style="text-align:center;">9-15</td>
            <td style="text-align:left;"><b>Horrific Scaring:</b> Gain a -2 penalty on all <i>Persuasion</i> checks and a +2 bonus on all <i>Intimidation</i> checks. Never heals naturally, but can be healed by the application of appropriate healing magic.</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:center;">16</td>
            <td style="text-align:left;"><b>Bruised Ribs:</b> Make a Diff 12 <i>Hardiness</i> save after each action in combat (or other physically strenuous activity). On a failure, gain 1 level of <i>Exhaustion</i>. Heals naturally on a Diff 12 CON check after a <i>Long Rest</i>, or by the application of appropriate healing magic.</td>
        </tr>
        <tr>
            <td style="text-align:center;">17</td>
            <td style="text-align:left;"><b>Sprained Knee/Ankle:</b> Your speed is reduced by 5 ft and you have <i>Disadvantage</i> on all <i>Evasion</i> saves. Heals naturally on a Diff 12 CON check after a <i>Long Rest</i>, or by the application of appropriate healing magic.</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:center;">18</td>
            <td style="text-align:left;"><b>Sprained Arm/Hand:</b> You have <i>Disadvantage</i> on any ability, skill or attack roll using the afflicted arm until healed. Heals naturally on a Diff 12 CON check after a <i>Long Rest</i>, or by the application of appropriate healing magic.</td>
        </tr>
        <tr>
            <td style="text-align:center;">19</td>
            <td style="text-align:left;"><b>Minor Concussion:</b> Make a Diff 12 <i>Hardiness</i> save after each action in combat (or other physically strenuous activity). On a failure, suffer the <i>Stunned</i> condition until the end of your next <i>Combat Turn</i>. Heals naturally on a Diff 12 CON check after a <i>Long Rest</i>, or by the application of appropriate healing magic.</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:center;">20</td>
            <td style="text-align:left;"><b>Heroic Scarring:</b> You have acquired a new scar. This has no mechanical effect.</td>
        </tr>
    </tbody>
</table>

## Combat Maneuvers

Once per *Combat Turn*, as part of a normal melee attack, anyone with the [Combat Mastery](classes/ClassAbilities.md#combat%20mastery) ability (such as [Fighters](classes/Fighter.md)) may declare a *Combat Maneuver* as part of their normal attack.  This is a special move that won't do any extra damage, but can add additional consequences to the attack (such as tripping or disarming a foe).  If the [Natural Roll](CoreRules.md#natural%20roll) shows a number equal to or higher than the character's *Combat Mastery* target, the move is successfully executed.  Some maneuvers allow the defender to negate the effect with a successful *Saving Throw* vs the total attack value rolled (see the below examples for details).

Characters without the *Combat Mastery* ability may also attempt **some** of these exploits (those marked with am asterisk) but this is done **instead** of a normal attack rather than in addition.  In this case, there is no need to roll to successfully execute the maneuver, but the target will still get a saving throw.  Characters with *Combat Mastery* may also choose this option, if they so wish.

### Combat Maneuver Examples:

#### Battle Cry
A roar, a shout, a stream of expletives; in some way you use voice and body language to try to unnerve your opponent.  You must be able to speak to use this maneuver.  The target must make a *Spirit Save* or become [Frightened](#frightened) until the **end** of their next *Combat Turn*.  This has no effect on mindless creatures or other beings immune to fear.

#### Blind*
From throwing sand in someone's face, to pulling their cloak hood over their eyes to slashing their brow so they bleed into their own eyes, you attempt  to impair your target's vision.  The target makes an *Evasion Save*.  On a failure, the target becomes [Blinded](#blinded) until the **end** of their next *Combat Turn*.  This obviously has no effect on creatures that don't use vision.

#### Charge*
Once per *Combat Encounter*, a character may make a Charge maneuver into melee combat.  The character must move at least 20 ft. in a straight line to count as a charge before getting into melee range.  When they make their attack, they do so with a +2 bonus, however, upon initiating this maneuver, the attacker gains a -2 penalty to their *AC* until the start of their next *Combat Turn*.  If the attacker's weapon has the [Lance property](EncumbranceAndEquipment.md#weapon%20properties), it rolls double the normal amount of damage dice on a hit.  If the defender's weapon has the [Set property](EncumbranceAndEquipment.md#weapon%20properties), and the defender has taken an action to actually set it, then they will get a free attack against the charging character and, if they hit, the weapon doubles its damage dice.  Finally, if one party's weapon has the [Reach property](EncumbranceAndEquipment.md#weapon%20properties) and the other does not, and the defender is *Set* against the charge, whomever has the reach weapon strikes first.

#### Disarm
You twist your target's weapon in such a way that they must pass an *Evasion Save* or it falls from their grasp.  Note that this only works on hand-held weapons, not natural weapons.  Weapons held in two hands make this save with *Advantage*.  If the save is failed, roll 1d10 to see where the target's weapon lands:

<table>
    <thead>
        <tr style="background-color:#708090;">
            <th id="d10" style="text-align:center;">d10</th>
            <th id="location" style="text-align:left;">Location</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;">At the target's own feet.</td>
        </tr>
        <tr>
            <td style="text-align:center;">2</td>
            <td style="text-align:left;">At the attacker's feet.</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:center;">3</td>
            <td style="text-align:left;">5 feet behind the defender.</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:center;">4</td>
            <td style="text-align:left;">5 feet to the defender's left.</td>
        </tr>
        <tr>
            <td style="text-align:center;">5</td>
            <td style="text-align:left;">5 feet to the defender's right.</td>
        </tr>
        <tr>
            <td style="text-align:center;">6</td>
            <td style="text-align:left;">5 feet in front of the defender.</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:center;">7</td>
            <td style="text-align:left;">5 feet to the defender's rear-left.</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:center;">8</td>
            <td style="text-align:left;">5 feet to the defender's rear-right.</td>
        </tr>
        <tr>
            <td style="text-align:center;">9</td>
            <td style="text-align:left;">5 feet to the defender's front-left.</td>
        </tr>
        <tr>
            <td style="text-align:center;">10</td>
            <td style="text-align:left;">5 feet to the defender's front-right.</td>
        </tr>
    </tbody>
</table>

#### Impair*
Striking at your foe's arm or hand, you attempt to weaken their ability to strike.  The target makes a *Hardiness Save*.  On a failure, they suffer *Disadvantage* on their next attack.  This cannot effect creatures immune to critical hits (such as undead and amorphous monsters).

#### Juke*
You fake going one direction in order to slip past your foe by going the other way around.  The target must make an *Evasion Save*.  On a failure, the attacker may use their movement to move through the target's space and to exit their reach without drawing a [Reflex Attack](#reactions) from the target.

#### Rally*
You let out a rallying cry, perform a flashy maneuver or otherwise attempt to embolden your allies.  Any ally within [Near](#range%20bands) range who can see and hear you adds your *Charisma Modifier* (minimum +1) their next morale or fear-based *Saving Throw* during this *Combat Encounter*.  Allies who already have broken morale or are [Frightened](#frightened) may immediately make a new save (adding your *CHA Mod*; min +1) to shake off the condition.

#### Shove*
You force your opponent to move a few steps back.  The target must make a *Hardiness Save*.  On a failure, they must step back 5 feet into an open space (either straight back, back-left or back-right) and the attacker may (if they so choose), step into the previously occupied space.  If there is no open space, the target loses their balance and attacks against them have *Advantage* until the start of their next *Combat Turn*.  If the target is larger than the attacker, or has more than two legs, they make their save with *Advantage*.  If they are smaller, they have *Disadvantage*.

#### Sweep
You attempt to swing your weapon through multiple targets at the same time.  This maneuver can only be done with [medium or heavy](EncumbranceAndEquipment.md#weight) melee weapons.  Pick 3 adjacent spaces within your melee reach.  A separate attack roll is made against each creature (friend or foe) within those spaces.  These attacks are made at -4 to hit.  If hit, a target takes damage as normal.  Characters with the [Minimum Damage](classes/ClassAbilities.md#minimum%20damage) ability do not benefit from that ability while using this maneuver.

#### Trip*
You try to take your opponent's feet out from under them.  The target must make an *Evasion Save*.  On a failure, they are knocked [Prone](#prone).  If the target is larger than the attacker, or has more than two legs, they make their save with *Advantage*.  If they are smaller, they have *Disadvantage*.  This has no effect on flying creatures or creatures without legs.

#### Wrest*
You attempt to grab an object currently in the possession of someone else.  An attack is made at -2 and, if successful, the attacker grabs hold of the object.  The attacker then must make a [contested Strength+Athletics check](CoreRules.md#contested%20checks) for control of the object.  Whomever wins takes sole possession of the object.  In the event of a tie, both parties have a grip on the object and neither may use it and either party may attempt another Strength+[Athletics](Skills.md#athletics) contest as their [main action](#main%20actions) on their subsequent *Combat Turns*.  Obviously, this maneuver requires at least 1 free hand to perform.

#### Other*
Describe some effect you wish to add to your attack.  The GM will decide what *Saving Throw* the target is allowed and the exact mechanical effects your maneuver has.
