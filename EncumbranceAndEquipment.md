# Encumbrance and Equipment

- [Encumbrance](#encumbrance)
- [Coinage](#coinage)
- [Equipment](#equipment)
	- [Quality](#quality)
	- [Rarity](#rarity)
	- [Haggling](#haggling)
	- [Weapons](#weapons)
		- [Weapon Properties](#weapon%20properties)
		- [Damage Types](#damage%20types)
		- [Weight](#weight)
		- [Ranges](#ranges)
		- [Melee Weapons](#melee%20weapons)
		- [Ranged Weapons](#ranged%20weapons)
	- [Armor](#armor)
		- [Armor Properties](#armor%20properties)
		- [Donning and Doffing Armor](#donning%20and%20doffing%20armor)
	- [Gear](#gear)
		- [Equipment Packs](#equipment%20packs)
		- [Food and Shelter](#food%20and%20shelter)
		- [Lifestyle Expenses](#lifestyle%20expenses)
		- [Services](#services)
		- [Mounts, Livestock and Transport](#mounts%20livestock%20and%20transport)
		- [Tack and Harness](#tack%20and%20harness)
		- [Drawn Vehicles](#drawn%20vehicles)

## Encumbrance
Any given character can only carry so much.  Some groups may wish to handwave the tracking of encumbrance and that's completely understandable.  The rules here are meant to provide some degree of verisimilitude without having to track pounds, ounces or "coins" of carried gear and treasure.

Encumbrance is tracked in 'Items' or 'Slots' (the terms are used interchangeably in these rules).  A single *Item* is any object that can be carried in one hand reasonably comfortably (a sword, a torch, a lute, etc).  Larger objects, take up at least 2 *Slots* (or more for even larger objects; like a full treasure chest).  Worn clothing does not count as an *Item*, but carried clothing does.  Small items (such as coins) do not count as an *Item* unless they are carried in bulk (such as 100 coins taking up 1 *Slot*). 

Additionally, some equipment may be *Bundled* to reduce the number of *Slots* they take up (such as a *Bundle* of 3 Torches only taking up *1 Slot*).  These *Bundles* require the *Ready an Item* [Main Action](Combat.md#main%20actions) to break apart for use after which the individual objects making up the *Bundle* must be tracked separately.

### Readied Items
Each character may carry a number of *Readied Items* equal to half their *Strength Score*, rounded up.  *Readied Items* are those items on hand for immediate use without needing to use the *Ready an Item* [Main Action](Combat.md#main%20actions) to unpack them.  This includes things like worn armor, carried shield, weapons and any other items the character wishes to be able to access quickly an easily.

### Stowed Items
*Stowed Items* are those packed away and carefully organized to be as compact as possible.  To carry any *Stowed Items*, a character must have a backpack, sack or similar thing in which to carry these items.  If so equipped, a character can carry as many *Stowed Items* as their *Strength Score*.  A character must use the [Ready an Item](Combat.md#main%20actions) action in order to access any *Stowed Items*.

### Excessive Encumbrance
These limits represent the amount of gear a character can carry without penalty.  An extra 2 *Readied Items* or 4 *Stowed Items* (or fractions thereof), reduces a character's Movement by 5 feet and they take a -2 penalty on all [Strength and Dexterity Checks](CoreRules.md#ability%20check).  Additionally, for every hour so encumbered, they must make a *Constitution Check* vs a [Difficulty of 12](CoreRules.md#difficulty) or gain a level of [Exhaustion](Conditions.md#exhaustion).  Going further beyond this limit; up to 4 *Readied Items* or 8 *Stowed Items*, reduces the character's movement to half, increases the *Strength and Dexterity check* penalties to -4 and increases the *Exhaustion Check Difficulty* to 15.

## Coinage
Every petty king and warlord seems to issue their own form of currency.  Below is a table listing those coin types most commonly found with sample regional names.  Most peasants and commoners deal in barter, but whey they do have coin, it is typically copper or (occasionally) silver.  Silver is typically the coin of merchants and other 'middle-class' folk. Higher value coins are rarely seen by the peasantry; mostly being used by wealthy merchants and nobles.

Even rarer still are ancient coins, gems, jewelry and the like.  Their value varies greatly by their rarity, quality and the seller's ability to find a collector.

The entries on the coinage table are far from the only materials used for money.  Some regions may use wood, bone, ivory or even more unusual materials.  Exchanges between countries is a matter of material value and diplomatic relations.

<table border=2>
	<tr style="background-color:#708090;">
		<th align="left"><b>Coin</b></th>
		<th align="center"><b>Abbr</b></th>
		<th align="left"><b>Name*</b></th>
		<th align="left"><b>Value</b></th>
		<th align="left"><b>Real World Equivalent</b></th>
	</tr>
	<tr>
		<td align="left">Copper</td>
		<td align="center">cp</td>
		<td align="left">Peasant</td>
		<td align="left">1/10sp</td>
		<td align="left">$1.00</td>
	</tr>
	<tr style="background-color:#91a3b0;">
		<td align="left">Silver</td>
		<td align="center">sp</td>
		<td align="left">Common</td>
		<td align="left">1sp</td>
		<td align="left">$10.00</td>
	</tr>
	<tr>
		<td align="left">Electrum</td>
		<td align="center">ep</td>
		<td align="left">Knight</td>
		<td align="left">5sp</td>
		<td align="left">$50.00</td>
	</tr>
	<tr style="background-color:#91a3b0;">
		<td align="left">Gold</td>
		<td align="center">gp</td>
		<td align="left">Noble</td>
		<td align="left">10sp</td>
		<td align="left">$100.00</td>
	</tr>
	<tr>
		<td align="left">Platinum</td>
		<td align="center">pp</td>
		<td align="left">Royal</td>
		<td align="left">100sp</td>
		<td align="left">$1,000.00</td>
	</tr>
	<tr style="background-color:#708090;">
		<td colspan=5>* Other realms will have their own names for equivalent coins.</td>
	</tr>
</table>

## Equipment

### Quality
The equipment table prices in this chapter assume items of common *Quality*.  Higher or lower *Quality* work can dramatically affect these prices.  The exact game effect of different *Quality* levels is often left up to the GM to determine on a case-by-case basis.  For example, a poor *Quality* sword may be judged to have a -1 to hit chance, while a Superior *Quality* sword may increase it’s damage die by 1 step.

<table border=2>
	<tr style="background-color:#708090;">
        <td align="center">Quality</td>
        <td align="center">Cost Multiplier</td>
    </tr>
    <tr>
        <td align="center">Poor</td>
        <td align="center">0.5</td>
    </tr>
	<tr style="background-color:#91a3b0;">
        <td align="center">Common</td>
        <td align="center">1</td>
    </tr>
    <tr>
        <td align="center">Excellent</td>
        <td align="center">2</td>
    </tr>
	<tr style="background-color:#91a3b0;">
        <td align="center">Superior</td>
        <td align="center">4</td>
    </tr>
    <tr>
        <td align="center">Master/Luxury</td>
        <td align="center">10</td>
    </tr>
</table>

### Rarity
Not all items are equally available in all regions.  As a result, the GM is encouraged to multiply the cost of an item based on how common or rare it is.  The recommended range is the same as for [Quality Modifiers](#quality) (x0.5 to x10).

### Haggling
It is possible that your players may wish to haggle with local merchants over the cost of items (especially for those with *Quality* or *Rarity* modifiers).  This can be handled with an [Opposed](CoreRules.md#contested%20checks) Charisma+[Persuasion](Skills.md#persuasion) check.  The following table lists the potential outcomes for that check.

<table border=2>
    <thead>
        <tr style="background-color:#708090;">
            <th id="outcome" style="text-align:left;">Outcome</th>
            <th id="result" style="text-align:left;">Result</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="text-align:left;">Fail by 8 or more</td>
            <td style="text-align:left;"><i>Hostility</i>: The merchant is insulted and throws the character out of their shop.  If they have any influence in the community, they may consider blacklisting the character with other merchants (*Disadvantage* on any further bartering rolls in this location for the next week).</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Fail by 5 to 7</td>
            <td style="text-align:left;"><i>Refusal</i>: The merchant not only refuses to haggle, but increases the price by (1d6+1d4)x10%.</td>
        </tr>
        <tr>
            <td style="text-align:left;">Fail by 1 to 5</td>
            <td style="text-align:left;"><i>Negotiation</i>: The merchant is potentially willing to make a compromise deal, changing their price by (2d4-5)x5% {-15% to +15%}</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Succeed by 0 to 2</td>
            <td style="text-align:left;"><i>Acceptance</i>: The merchant agrees to reduce their price by up to 30%.</td>
        </tr>
        <tr>
            <td style="text-align:left;">Succeed by 3+</td>
            <td style="text-align:left;"><i>Eager Acceptance</i>: The character has won the merchant over to such a degree that they’re willing to offer a ‘friends and family’ discount, cutting their price by up to 50%.</td>
        </tr>
    </tbody>
</table>  

If the characters have no intent to haggle, simply forego any haggling rolls and use the price as listed (modified by quality and rarity as normal).

### Weapons
The weapon tables below are not meant to be exhaustive, but represent those most commonly found in a typical western-style fantasy campaign.  For more exotic weaponry from far off lands, it’s often easiest to simply find an equivalent entry on one of the below tables and modify it’s stats based on quality and rarity.  For example, a katana could be interpreted as a [Rare](#rarity) _Excellent_-[Quality](#quality) arming sword (+1 to hit, x4 cost).

#### Weapon Quality
When it comes to weapons of higher or lower [Quality](#quality), it is recommended that modifiers be limited to no more than +/- 1 on to-hit or damage, or a 1 die step for damage.  Higher *Quality* weapons might have multiple such properties (such as a master-crafted bow being +1 to hit, +1 die step damage and +10% range).
  
#### Weapon Properties
- **2H**: This weapon requires 2 hands to wield.
- **Defensive**: Wielding this weapon with proficiency grants the user +1 AC in melee.
- **Finesse**: When used in melee, this weapon may use either *Dexterity* or *Strength* for attack and damage modifiers.
- **Flexible**: This weapon ignores the target's AC bonus from shields and weapons with the *Defensive* property.
- **Hurlant**: This weapon may be thrown to a range of [Near](#ranges) using either *Strength* or *Dexterity* for attack and damage bonuses.
- **Impact**: On a *Critical Hit* the target suffers the effects of a [Shove](Combat.md#shove).
- **Lance**: This weapon requires 2-hands when used on foot, but only 1 hand when mounted. Additionally, it does double damage on a mounted [Charge Maneuver](Combat.md#charge).
- **Reach**: This weapon can be used for melee attacks against targets out to 10ft and can be used from the 2nd rank.
- **Reload**: This weapon must be reloaded after each use, requiring a [Main Action](Combat.md#main%20actions).
- **Snare**: A large or smaller creature hit by this weapon is [Restrained](Conditions.md#restrained). A *Restrained* creature may spend a *Main Action* to attempt a [Dexterity Check](CoreRules.md#ability%20check) vs a [Difficulty](CoreRules.md#difficulty) equal to the Attack Roll total to escape.  Alternatively, a *Difficulty 15 Strength Check* may be attempted to break the ensnaring weapon.
- **Versatile**: This weapon may be wielded with either 1 or 2 hands.  If 2 hands are used, roll damage with *Advantage*.  Small creatures using this weapon one-handed have *Disadvantage* on their *Attack Rolls*.  If they use 2 hands they do **not** roll damage with *Advantage*.

#### Damage Types
- **(B)lunt**
- **(P)iercing**
- **(S)lashing**

If a weapon lists 2 or more [Damage Types](CoreRules.md#damage%20types), the wielder must specify the *Damage Type* they are using when they make the attack.  If not specified, the first listed type will be assumed.

#### Weight
- **(L)ight**: Anyone can use these weapons in their off-hand.
- **(M)edium**: No special notes.
- **(H)eavy**: Small creatures have *Disadvantage* when wielding weapons with this tag.

#### Ranges
- **(C)lose**: 5 feet - Weapons with a [range](Combat.md#range%20bands) of *Far* have *Disadvantage* at this range.
- **(N)ear**: 30 feet
- **(F)ar**: 150 feet - Attacks made at this range or further have *Disadvantage*.
- **(S)ight**: Within Line of Sight (LoS).
- **(D)istant**: Beyond perception.

#### Melee Weapons
<table border=2>
	<tr style="background-color:#708090;">
        <td>Weapon</td>
        <td align="center">Weight</td>
        <td align="center">Damage</td>
        <td align="center">Type</td>
        <td align="center">Cost</td>
        <td align="center">Slots</td>
        <td>Properties</td>
    </tr>
    <tr>
        <td>Axe, Battle</td>
        <td align="center">M</td>
        <td align="center">1d8</td>
        <td align="center">S/B or S/P</td>
        <td align="right">20sp</td>
        <td align="center">1</td>
        <td>Versatile, Impact</td>
    </tr>
    <tr>
        <td>Axe, Great</td>
        <td align="center">H</td>
        <td align="center">1d10</td>
        <td align="center">S/B</td>
        <td align="right">60sp</td>
        <td align="center">2</td>
        <td>2H, Impact</td>
    </tr>
	<tr style="background-color:#91a3b0;">
        <td>Axe, Hand / Hatchet</td>
        <td align="center">L</td>
        <td align="center">1d6</td>
        <td align="center">S/B</td>
        <td align="right">10sp</td>
        <td align="center">1</td>
        <td>Hurlant</td>
    </tr>
	<tr style="background-color:#91a3b0;">
        <td>Bardiche</td>
        <td align="center">H</td>
        <td align="center">1d10</td>
        <td align="center">S/B</td>
        <td align="right">40sp</td>
        <td align="center">2</td>
        <td>Reach, 2H, Impact</td>
    </tr>
    <tr>
        <td>Bec de Corbyn / Pole Hammer</td>
        <td align="center">H</td>
        <td align="center">1d10</td>
        <td align="center">B/P</td>
        <td align="right">40sp</td>
        <td align="center">2</td>
        <td>Reach, 2H, Impact, Set</td>
    </tr>
    <tr>
        <td>Buckler</td>
        <td align="center">L</td>
        <td align="center">1d4</td>
        <td align="center">B</td>
        <td align="right">10sp</td>
        <td align="center">1</td>
        <td>Finesse, Defensive</td>
    </tr>
	<tr style="background-color:#91a3b0;">
        <td>Club</td>
        <td align="center">L</td>
        <td align="center">1d4</td>
        <td align="center">B</td>
        <td align="right">1cp</td>
        <td align="center">1</td>
        <td>--</td>
    </tr>
	<tr style="background-color:#91a3b0;">
        <td>Club, Great</td>
        <td align="center">H</td>
        <td align="center">1d8</td>
        <td align="center">B</td>
        <td align="right">1sp</td>
        <td align="center">2</td>
        <td>2H, Impact</td>
    </tr>
    <tr>
        <td>Dagger</td>
        <td align="center">L</td>
        <td align="center">1d6</td>
        <td align="center">P/S</td>
        <td align="right">4sp</td>
        <td align="center">1</td>
        <td>Finesse, Hurlant</td>
    </tr>
    <tr>
        <td>Flail</td>
        <td align="center">M</td>
        <td align="center">1d8</td>
        <td align="center">B</td>
        <td align="right">20sp</td>
        <td align="center">1</td>
        <td>Impact, Flexible</td>
    </tr>
	<tr style="background-color:#91a3b0;">
        <td>Flail, Heavy</td>
        <td align="center">H</td>
        <td align="center">1d10</td>
        <td align="center">B</td>
        <td align="right">25sp</td>
        <td align="center">2</td>
        <td>2H, Impact, Flexible</td>
    </tr>
	<tr style="background-color:#91a3b0;">
        <td>Halberd / Poleaxe / Bill / Glaive</td>
        <td align="center">H</td>
        <td align="center">1d10</td>
        <td align="center">S/P</td>
        <td align="right">40sp</td>
        <td align="center">2</td>
        <td>Reach, 2H, Impact, Set</td>
    </tr>
    <tr>
        <td>Hammer, Light</td>
        <td align="center">M</td>
        <td align="center">1d6</td>
        <td align="center">B</td>
        <td align="right">10sp</td>
        <td align="center">1</td>
        <td>Hurlant</td>
    </tr>
    <tr>
        <td>Hammer, Maul</td>
        <td align="center">H</td>
        <td align="center">1d10</td>
        <td align="center">B</td>
        <td align="right">50sp</td>
        <td align="center">2</td>
        <td>2H, Impact</td>
    </tr>
	<tr style="background-color:#91a3b0;">
        <td>Hammer, War</td>
        <td align="center">M</td>
        <td align="center">1d8</td>
        <td align="center">B/P</td>
        <td align="right">30sp</td>
        <td align="center">1</td>
        <td>Versatile, Impact</td>
    </tr>
	<tr style="background-color:#91a3b0;">
        <td>Improvised</td>
        <td align="center">?</td>
        <td align="center">?</td>
        <td align="center">?</td>
        <td align="right">--</td>
        <td align="center">1</td>
        <td></td>
    </tr>
    <tr>
        <td>Javelin (3)</td>
        <td align="center">M</td>
        <td align="center">1d6</td>
        <td align="center">P</td>
        <td align="right">3sp</td>
        <td align="center">1</td>
        <td>Versatile, Hurlant</td>
    </tr>
    <tr>
        <td>Lance</td>
        <td align="center">H</td>
        <td align="center">1d10</td>
        <td align="center">P</td>
        <td align="right">20sp</td>
        <td align="center">1</td>
        <td>Reach, Lance, Impact</td>
    </tr>
	<tr style="background-color:#91a3b0;">
        <td>Mace</td>
        <td align="center">M</td>
        <td align="center">1d8</td>
        <td align="center">B</td>
        <td align="right">15sp</td>
        <td align="center">1</td>
        <td>Impact</td>
    </tr>
	<tr style="background-color:#91a3b0;">
        <td>Mace, Great</td>
        <td align="center">H</td>
        <td align="center">1d10</td>
        <td align="center">B</td>
        <td align="right">25sp</td>
        <td align="center">2</td>
        <td>2H, Impact</td>
    </tr>
    <tr>
        <td>Morning Star</td>
        <td align="center">M</td>
        <td align="center">1d8</td>
        <td align="center">B</td>
        <td align="right">30sp</td>
        <td align="center">1</td>
        <td>Versatile, Impact</td>
    </tr>
    <tr>
        <td>Net</td>
        <td align="center">M</td>
        <td align="center">--</td>
        <td align="center">--</td>
        <td align="right">2sp</td>
        <td align="center">2</td>
        <td>Flexible, Hurlant, Snare, 2H</td>
    </tr>
	<tr style="background-color:#91a3b0;">
        <td>Pike</td>
        <td align="center">H</td>
        <td align="center">1d10</td>
        <td align="center">P</td>
        <td align="right">4sp</td>
        <td align="center">2</td>
        <td>Reach, 2H, Set</td>
    </tr>
	<tr style="background-color:#91a3b0;">
        <td>Quarterstaff</td>
        <td align="center">M</td>
        <td align="center">1d6</td>
        <td align="center">B</td>
        <td align="right">5cp</td>
        <td align="center">1</td>
        <td>Defensive, Versatile</td>
    </tr>
    <tr>
        <td>Spear</td>
        <td align="center">M</td>
        <td align="center">1d8</td>
        <td align="center">P</td>
        <td align="right">2sp</td>
        <td align="center">1</td>
        <td>Versatile, Hurlant, Set</td>
    </tr>
    <tr>
        <td>Sword, Arming</td>
        <td align="center">M</td>
        <td align="center">1d8</td>
        <td align="center">S/P</td>
        <td align="right">30sp</td>
        <td align="center">1</td>
        <td>Versatile</td>
    </tr>
	<tr style="background-color:#91a3b0;">
        <td>Sword, Long / Great</td>
        <td align="center">H</td>
        <td align="center">1d10</td>
        <td align="center">S</td>
        <td align="right">100sp</td>
        <td align="center">2</td>
        <td>2H, Impact</td>
    </tr>
	<tr style="background-color:#91a3b0;">
        <td>Sword, Rapier</td>
        <td align="center">M</td>
        <td align="center">1d8</td>
        <td align="center">P</td>
        <td align="right">50sp</td>
        <td align="center">1</td>
        <td>Finesse</td>
    </tr>
    <tr>
        <td>Sword, Saber / Scimitar</td>
        <td align="center">M</td>
        <td align="center">1d8</td>
        <td align="center">S</td>
        <td align="right">50sp</td>
        <td align="center">1</td>
        <td>Finesse</td>
    </tr>
    <tr>
        <td>Sword, Short</td>
        <td align="center">L</td>
        <td align="center">1d6</td>
        <td align="center">S/P</td>
        <td align="right">20sp</td>
        <td align="center">1</td>
        <td>Finesse</td>
    </tr>
	<tr style="background-color:#91a3b0;">
        <td>Sword, Small</td>
        <td align="center">L</td>
        <td align="center">1d6</td>
        <td align="center">P/S</td>
        <td align="right">24sp</td>
        <td align="center">1</td>
        <td>Finesse</td>
    </tr>
	<tr style="background-color:#91a3b0;">
        <td>Trident</td>
        <td align="center">M</td>
        <td align="center">1d8+1</td>
        <td align="center">P</td>
        <td align="right">10sp</td>
        <td align="center">1</td>
        <td>Versatile, Hurlant, Set</td>
    </tr>
    <tr>
        <td>Unarmed*</td>
        <td align="center">L</td>
        <td align="center">1d2</td>
        <td align="center">B</td>
        <td align="right">--</td>
        <td align="center">0</td>
        <td>Finesse</td>
    </tr>
    <tr>
        <td>War Pick</td>
        <td align="center">M</td>
        <td align="center">1d8</td>
        <td align="center">P</td>
        <td align="right">10sp</td>
        <td align="center">1</td>
        <td>Versatile</td>
    </tr>
	<tr style="background-color:#91a3b0;">
        <td>Whip</td>
        <td align="center">L</td>
        <td align="center">1d6</td>
        <td align="center">S</td>
        <td align="right">4sp</td>
        <td align="center">1</td>
        <td>Finesse, Reach, Snare, Flexible</td>
    </tr>
    <tr style="background-color:#708090;">
	    <td colspan=7>? -- These properties must be decided upon by the GM when the improvised weapon is acquired.<br/>* -- All characters are always proficient with unarmed combat.</td>
    </tr>
</table>

#### Ranged Weapons  
<table border=2>
    <thead>
        <tr style="background-color:#708090;">
            <th id="weapon"
                style="text-align:left;">Weapon</th>
            <th id="weight"
                style="text-align:center;">Weight</th>
            <th id="damage"
                style="text-align:center;">Damage</th>
            <th id="type"
                style="text-align:center;">Type</th>
            <th id="range"
                style="text-align:center;">Range</th>
            <th id="cost"
                style="text-align:right;">Cost</th>
            <th id="slots"
                style="text-align:center;">Slots</th>
            <th id="properties"
                style="text-align:left;">Properties</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="text-align:left;">Axe, Hand / Hatchet</td>
            <td style="text-align:center;">L</td>
            <td style="text-align:center;">1d6</td>
            <td style="text-align:center;">S/B</td>
            <td style="text-align:center;">N</td>
            <td style="text-align:right;">10sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;">Hurlant</td>
        </tr>
        <tr>
            <td style="text-align:left;">Blowgun</td>
            <td style="text-align:center;">L</td>
            <td style="text-align:center;">1d4</td>
            <td style="text-align:center;">P</td>
            <td style="text-align:center;">N</td>
            <td style="text-align:right;">20sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;">Reload</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Bola</td>
            <td style="text-align:center;">L</td>
            <td style="text-align:center;">1d4</td>
            <td style="text-align:center;">B</td>
            <td style="text-align:center;">N</td>
            <td style="text-align:right;">1sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;">Snare, Hurlant</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Bow, Long</td>
            <td style="text-align:center;">H</td>
            <td style="text-align:center;">1d8</td>
            <td style="text-align:center;">P</td>
            <td style="text-align:center;">F</td>
            <td style="text-align:right;">100sp</td>
            <td style="text-align:center;">2</td>
            <td style="text-align:left;">2H</td>
        </tr>
        <tr>
            <td style="text-align:left;">Bow, Short</td>
            <td style="text-align:center;">M</td>
            <td style="text-align:center;">1d6</td>
            <td style="text-align:center;">P</td>
            <td style="text-align:center;">F</td>
            <td style="text-align:right;">50sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;">2H</td>
        </tr>
        <tr>
            <td style="text-align:left;">Crossbow</td>
            <td style="text-align:center;">M</td>
            <td style="text-align:center;">1d8</td>
            <td style="text-align:center;">P</td>
            <td style="text-align:center;">F</td>
            <td style="text-align:right;">75sp</td>
            <td style="text-align:center;">2</td>
            <td style="text-align:left;">Reload, 2H</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Crossbow, Heavy</td>
            <td style="text-align:center;">H</td>
            <td style="text-align:center;">1d10</td>
            <td style="text-align:center;">P</td>
            <td style="text-align:center;">F</td>
            <td style="text-align:right;">150sp</td>
            <td style="text-align:center;">2</td>
            <td style="text-align:left;">Reload, 2H</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Crossbow, Pistol</td>
            <td style="text-align:center;">L</td>
            <td style="text-align:center;">1d6</td>
            <td style="text-align:center;">P</td>
            <td style="text-align:center;">N</td>
            <td style="text-align:right;">200sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;">Reload</td>
        </tr>
        <tr>
            <td style="text-align:left;">Dagger</td>
            <td style="text-align:center;">L</td>
            <td style="text-align:center;">1d6</td>
            <td style="text-align:center;">P/S</td>
            <td style="text-align:center;">N</td>
            <td style="text-align:right;">4sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;">Finesse, Hurlant</td>
        </tr>
        <tr>
            <td style="text-align:left;">Darts (10)</td>
            <td style="text-align:center;">L</td>
            <td style="text-align:center;">1d4</td>
            <td style="text-align:center;">P</td>
            <td style="text-align:center;">N</td>
            <td style="text-align:right;">1sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;">Finesse, Hurlant</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Hammer, Light</td>
            <td style="text-align:center;">M</td>
            <td style="text-align:center;">1d6</td>
            <td style="text-align:center;">B</td>
            <td style="text-align:center;">N</td>
            <td style="text-align:right;">10sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;">Hurlant</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Improvised</td>
            <td style="text-align:center;">?</td>
            <td style="text-align:center;">?</td>
            <td style="text-align:center;">?</td>
            <td style="text-align:center;">N</td>
            <td style="text-align:right;">--</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr>
            <td style="text-align:left;">Javelin (3)</td>
            <td style="text-align:center;">M</td>
            <td style="text-align:center;">1d6</td>
            <td style="text-align:center;">P</td>
            <td style="text-align:center;">N</td>
            <td style="text-align:right;">3sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;">Versatile, Hurlant</td>
        </tr>
        <tr>
            <td style="text-align:left;">Lasso</td>
            <td style="text-align:center;">L</td>
            <td style="text-align:center;">--</td>
            <td style="text-align:center;">--</td>
            <td style="text-align:center;">N</td>
            <td style="text-align:right;">4cp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;">Snare, Flexible, Hurlant</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Net</td>
            <td style="text-align:center;">M</td>
            <td style="text-align:center;">--</td>
            <td style="text-align:center;">--</td>
            <td style="text-align:center;">N</td>
            <td style="text-align:right;">2sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;">Hurlant, Snare, 2H, Flexible</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Sling</td>
            <td style="text-align:center;">L</td>
            <td style="text-align:center;">1d6</td>
            <td style="text-align:center;">B</td>
            <td style="text-align:center;">F</td>
            <td style="text-align:right;">2cp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr>
            <td style="text-align:left;">Spear</td>
            <td style="text-align:center;">M</td>
            <td style="text-align:center;">1d8</td>
            <td style="text-align:center;">P</td>
            <td style="text-align:center;">N</td>
            <td style="text-align:right;">2sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;">Versatile, Hurlant</td>
        </tr>
        <tr>
            <td style="text-align:left;">Trident</td>
            <td style="text-align:center;">M</td>
            <td style="text-align:center;">1d8+1</td>
            <td style="text-align:center;">P</td>
            <td style="text-align:center;">N</td>
            <td style="text-align:right;">1 0sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;">Versatile, Hurlant</td>
        </tr>
        <tr style="background-color:#708090;">
            <td colspan=8>? -- These properties must be decided upon by the GM when the improvised weapon is acquired.</td>
        </tr>
    </tbody>
</table>

### Armor
The armor list below should be considered as general categories of armor rather than a definitive list.  There are too many types of armor in both history and fantasy to create a truly exhaustive list and, instead, armor should be associated with its nearest category to determine it’s game mechanics.

Like other items, armor [Quality](#quality) can vary.  It is generally recommended that any one characteristic not be modified by more than one step better or worse.  *Qualities* higher than Good should simply modify multiple characteristics.

#### Armor Properties
- **1H**: Requires the use of 1 hand.
- **Weight**: This is the armor category noted for proficiency purposes 
	- (L)ight, (M)edium, (H)eavy, (B)uckler and (S)hield.
- **Encumbering**: Reduces movement by 10ft (for Medium armor) or 20ft (for Heavy armor).  Also for every 1 minute of intense activity (such as [combat](Combat.md)), make a [Constitution Check](CoreRules.md#ability%20check) vs [Difficulty](CoreRules.md#difficulty) 13 (Medium) or 15 (Heavy) or gain 1 level of [Exhaustion](Conditions.md#exhaustion).
- **Noisy**: Imposes *Disadvantage* on [stealth](Skills.md#stealth) checks.
- **DEX Mod**: This is the amount of your *Dexterity Modifier* (round up) that may be added to your AC.  If your Dexterity modifier is negative, always apply the full value.

#### Armor Table
<table border=2>
    <thead>
        <tr style="background-color:#708090;">
            <th id="type" style="text-align:left;">Type</th>
            <th id="category" style="text-align:center;">Weight</th>
            <th id="base_ac" style="text-align:center;">Base AC</th>
            <th id="dex_mod" style="text-align:center;">DEX Mod</th>
            <th id="cost" style="text-align:right;">Cost</th>
            <th id="slots" style="text-align:center;">Slots*</th>
            <th id="properties" style="text-align:left;">Properties</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="text-align:left;">Cloth / Leather</td>
            <td style="text-align:center;">L</td>
            <td style="text-align:center;">+1</td>
            <td style="text-align:center;">Full</td>
            <td style="text-align:right;">10sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;">--</td>
        </tr>
        <tr>
            <td style="text-align:left;">Hardened Leather</td>
            <td style="text-align:center;">L</td>
            <td style="text-align:center;">+2</td>
            <td style="text-align:center;">Full</td>
            <td style="text-align:right;">40sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;">--</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Ringmail</td>
            <td style="text-align:center;">M</td>
            <td style="text-align:center;">+3</td>
            <td style="text-align:center;">Half</td>
            <td style="text-align:right;">100sp</td>
            <td style="text-align:center;">2</td>
            <td style="text-align:left;">Noisy</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Scalemail</td>
            <td style="text-align:center;">M</td>
            <td style="text-align:center;">+4</td>
            <td style="text-align:center;">Half</td>
            <td style="text-align:right;">300sp</td>
            <td style="text-align:center;">2</td>
            <td style="text-align:left;">Noisy, Encumbering</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Chainmail</td>
            <td style="text-align:center;">M</td>
            <td style="text-align:center;">+5</td>
            <td style="text-align:center;">Half</td>
            <td style="text-align:right;">600sp</td>
            <td style="text-align:center;">2</td>
            <td style="text-align:left;">Noisy, Encumbering</td>
        </tr>
        <tr>
            <td style="text-align:left;">Reinforced Chain</td>
            <td style="text-align:center;">H</td>
            <td style="text-align:center;">+6</td>
            <td style="text-align:center;">Zero</td>
            <td style="text-align:right;">1,000sp</td>
            <td style="text-align:center;">3</td>
            <td style="text-align:left;">Noisy, Encumbering</td>
        </tr>
        <tr>
            <td style="text-align:left;">Lamellar</td>
            <td style="text-align:center;">H</td>
            <td style="text-align:center;">+7</td>
            <td style="text-align:center;">Zero</td>
            <td style="text-align:right;">2,000sp</td>
            <td style="text-align:center;">3</td>
            <td style="text-align:left;">Noisy, Encumbering</td>
        </tr>
        <tr>
            <td style="text-align:left;">Plate</td>
            <td style="text-align:center;">H</td>
            <td style="text-align:center;">+8</td>
            <td style="text-align:center;">Zero</td>
            <td style="text-align:right;">3,000sp</td>
            <td style="text-align:center;">3</td>
            <td style="text-align:left;">Noisy, Encumbering</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Buckler</td>
            <td style="text-align:center;">B</td>
            <td style="text-align:center;">#</td>
            <td style="text-align:center;">--</td>
            <td style="text-align:right;">10sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;">1H</td>
        </tr>
        <tr>
            <td style="text-align:left;">Shield</td>
            <td style="text-align:center;">S</td>
            <td style="text-align:center;">%</td>
            <td style="text-align:center;">--</td>
            <td style="text-align:right;">20sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;">1H</td>
        </tr>
        <tr style="background-color:#708090;">
            <td colspan=7>* Slot size is for armor worn.  For armor carried, double the number of Slots needed.<br/># Grants +3 AC with no armor, +2 with Light armor, +1 with Medium and +0 with Heavy.<br/>% Grants +4 AC with no armor, +3 with Light, +2 with Medium and +1 with Heavy.</td>
        </tr>
    </tbody>
</table>

For creatures that are not *Medium* in [Size](Beastiary.md#size%20category), the cost of armor is modified: For *Small* creatures, costs are halved.  For creatures of *Large* size or greater, the cost doubles per *Size Category* larger than *Medium*.  The [Slot](#encumbrance) values are not adjusted.

#### Donning and Doffing Armor
It takes time to don (put on) or doff (take off) armor.  You only benefit from armor's AC bonus once it is fully on (after the full donning time).

<table border=2>
    <thead>
        <tr style="background-color:#708090;">
            <th id="category" style="text-align:left;">Weight</th>
            <th id="don" style="text-align:right;">Don</th>
            <th id="doff" style="text-align:right;">Doff</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="text-align:left;">Light*</td>
            <td style="text-align:right;">1 minute</td>
            <td style="text-align:right;">1 minute</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Medium*</td>
            <td style="text-align:right;">5 minutes</td>
            <td style="text-align:right;">1 minute</td>
        </tr>
        <tr>
            <td style="text-align:left;">Heavy*</td>
            <td style="text-align:right;">10 minutes</td>
            <td style="text-align:right;">5 minutes</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Buckler / Shield</td>
            <td style="text-align:right;">1 action</td>
            <td style="text-align:right;">1 action</td>
        </tr>
        <tr style="background-color:#708090;">
            <td colspan=3>* Halve the Don and Doff times if a competent assistant is available.</td>
        </tr>
    </tbody>
</table>

#### Armor Training
A character may have been trained in the proper wearing and movement for Light, Medium and Heavy armor through either a Class Ability or [Trait](Traits.md#Armor%20Training%20(light,%20medium%20or%20heavy)).  While wearing armor they have not been trained in, a character will suffer Disadvantage on all their [Physical Checks](Glossary.md#physical%20check).

### Gear
This is a list of common adventuring gear, much of which can be found in various general stores throughout the land.  Some specialized items (such as Acid, Alchemist’s Fire, Poisons and the like) will only be available at specialty shops like alchemy shops, herbalists and so forth.

<table border=2>
    <thead>
        <tr style="background-color:#708090;">
            <th id="item" style="text-align:left;">Item</th>
            <th id="cost" style="text-align:right;">Cost</th>
            <th id="slots" style="text-align:center;">Slots</th>
            <th id="properties" style="text-align:left;">Properties</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="text-align:left;">Acid (flask)</td>
            <td style="text-align:right;">50sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;">Hurlant; 5ft Splash; 1d6 acid damage per round for 2p4 rounds</td>
        </tr>
        <tr>
            <td style="text-align:left;">Alchemist's Fire (flask)</td>
            <td style="text-align:right;">100sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;">Hurlant; 5ft splash; 1d8 fire damage per round for 2p6 rounds</td>
        </tr>
        <tr>
            <td style="text-align:left;"><em>Ammunition</em></td>
            <td style="text-align:right;">--</td>
            <td style="text-align:center;">--</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">-Arrows (20)</td>
            <td style="text-align:right;">2sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">-Blowgun Needles (50)</td>
            <td style="text-align:right;">2sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">-Crossbow Bolts (20)</td>
            <td style="text-align:right;">2sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">-Sling Bullets (20)</td>
            <td style="text-align:right;">2cp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr>
            <td style="text-align:left;">Antitoxin (2 doses)</td>
            <td style="text-align:right;">100sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;"><i>Advantage</i> on <i>Hardiness Saves</i> and <i>CON Checks</i> vs Poison.</td>
        </tr>
        <tr>
            <td style="text-align:left;">Backpack</td>
            <td style="text-align:right;">4sp</td>
            <td style="text-align:center;">*</td>
            <td style="text-align:left;">Can carry up to 10 <i>Stowed Items</i>.</td>
        </tr>
        <tr>
            <td style="text-align:left;">Bedroll &amp; Blanket</td>
            <td style="text-align:right;">2sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Book</td>
            <td style="text-align:right;">50sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;">Grants <i>Advantage</i> on <i>Lore</i> checks for one specific subject.</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Caltrops (1 bag)</td>
            <td style="text-align:right;">2sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;">Covers a 10ft area creating <i>Difficult Terrain</i> and does 1d4 piercing damage on a failed  <i>Evasion Save</i> vs <i>Difficulty 12</i>.</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Candles (5)</td>
            <td style="text-align:right;">2cp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;">5ft dim light for 1 hour each.</td>
        </tr>
        <tr>
            <td style="text-align:left;">Chest, Small</td>
            <td style="text-align:right;">10sp</td>
            <td style="text-align:center;">2</td>
            <td style="text-align:left;">Can hold up to 10 Stowed <i>Items</i>.</td>
        </tr>
        <tr>
            <td style="text-align:left;">Chest, Large</td>
            <td style="text-align:right;">100sp</td>
            <td style="text-align:center;">4</td>
            <td style="text-align:left;">Can hold up to 30 Stowed <i>Items</i>.</td>
        </tr>
        <tr>
            <td style="text-align:left;">Climber's Kit</td>
            <td style="text-align:right;">50sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;">Grants +2 on all climbing checks.</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Cloak</td>
            <td style="text-align:right;">1sp</td>
            <td style="text-align:center;">*</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Clothing</td>
            <td style="text-align:right;">2cp</td>
            <td style="text-align:center;">*</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Coins (100)</td>
            <td style="text-align:right;">var</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr>
            <td style="text-align:left;">Crowbar</td>
            <td style="text-align:right;">10sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;">Grants <i>Advantage</i> on STR Checks if leverage applies. May be used as an improvised weapon doing 1d6 blunt damage at -1 to hit.</td>
        </tr>
        <tr>
            <td style="text-align:left;">Disguise Kit</td>
            <td style="text-align:right;">20sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr>
            <td style="text-align:left;">Flask / Bottle</td>
            <td style="text-align:right;">4sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;">Holds 1 qt of liquid</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;"><em>Games</em></td>
            <td style="text-align:right;">--</td>
            <td style="text-align:center;">--</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">-Cards (deck)</td>
            <td style="text-align:right;">2cp</td>
            <td style="text-align:center;">@</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">-Dice</td>
            <td style="text-align:right;">2cp</td>
            <td style="text-align:center;">#</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">-Board</td>
            <td style="text-align:right;">1sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;">chess, backgammon or the like</td>
        </tr>
        <tr>
            <td style="text-align:left;">Gems</td>
            <td style="text-align:right;">var</td>
            <td style="text-align:center;">@</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr>
            <td style="text-align:left;">Grappling Hook</td>
            <td style="text-align:right;">4sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr>
            <td style="text-align:left;">Hammer</td>
            <td style="text-align:right;">2sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;">May be used as an improvised weapon doing 1d4 blunt damage at -1 to hit</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Hammer, Sledge</td>
            <td style="text-align:right;">4sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;">May be used as an improvised weapon doing 1d8 blunt damage at -1 to hit; 2 hands</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Healer's Kit</td>
            <td style="text-align:right;">10sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;">has 10 uses</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Holy Symbol</td>
            <td style="text-align:right;">10sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;">May be used as a Magical Focus for religiously inclined spellcasters, but then costs 100sp due to the extra preparations and blessings needed.</td>
        </tr>
        <tr>
            <td style="text-align:left;">Holy Water (flask)</td>
            <td style="text-align:right;">50sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;">Hurlant; 5ft splash; 1d6 radiant damage to targets vulnerable to radiant damage.</td>
        </tr>
        <tr>
            <td style="text-align:left;">Ink (vial)</td>
            <td style="text-align:right;">20sp</td>
            <td style="text-align:center;">@</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr>
            <td style="text-align:left;">Iron Spikes / Pitons (10)</td>
            <td style="text-align:right;">1sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Ladder (10ft)</td>
            <td style="text-align:right;">2cp</td>
            <td style="text-align:center;">2</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Lantern</td>
            <td style="text-align:right;">10sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;">30ft bright light plus 30ft dim light for 1 <i>Watch</i>.</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Lock</td>
            <td style="text-align:right;">20sp</td>
            <td style="text-align:center;">@</td>
            <td style="text-align:left;">Difficilty 15 to pick or Diff 18 to break.</td>
        </tr>
        <tr>
            <td style="text-align:left;">Lockpicks</td>
            <td style="text-align:right;">25sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr>
            <td style="text-align:left;">Locksmith's Kit</td>
            <td style="text-align:right;">50sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;">In addition to counting as lockpicks, can also be used to repair and construct locks.</td>
        </tr>
        <tr>
            <td style="text-align:left;">Manacles</td>
            <td style="text-align:right;">4sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;">Difficulty 15 to pick or Diff 18 to break.</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Mess Kit</td>
            <td style="text-align:right;">3sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Mirror, Steel</td>
            <td style="text-align:right;">10sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Musical Instrument</td>
            <td style="text-align:right;">20sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr>
            <td style="text-align:left;">Oil (flask)</td>
            <td style="text-align:right;">2cp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr>
            <td style="text-align:left;">Paper (10 sheets)</td>
            <td style="text-align:right;">4sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr>
            <td style="text-align:left;">Parchment (5 sheets)</td>
            <td style="text-align:right;">1sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Poison, basic (2 doses)</td>
            <td style="text-align:right;">200sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;">Victim must make a Difficulty 15 <i>Hardiness Save</i> or become <i>Poisoned</i> for 3p6 rounds and takes 1d6 poison damage per round.</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Pole, 10ft</td>
            <td style="text-align:right;">2cp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Quill (10)</td>
            <td style="text-align:right;">4cp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr>
            <td style="text-align:left;">Rations (1 day)</td>
            <td style="text-align:right;">1sp</td>
            <td style="text-align:center;">1/2</td>
            <td style="text-align:left;">1 day's food &amp; water</td>
        </tr>
        <tr>
            <td style="text-align:left;">Rations (1 wk)</td>
            <td style="text-align:right;">5sp</td>
            <td style="text-align:center;">2</td>
            <td style="text-align:left;"><i>Bundle</i> of 7 days' rations.</td>
        </tr>
        <tr>
            <td style="text-align:left;">Rope, 50ft</td>
            <td style="text-align:right;">2sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Sack</td>
            <td style="text-align:right;">1sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;">Holds 10 slots worth of Stowed gear but takes up 1 hand.</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Shovel</td>
            <td style="text-align:right;">4sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;">May be used as an improvised club doing 1d6 blunt damage at -1 to hit.</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Signet Ring</td>
            <td style="text-align:right;">10sp</td>
            <td style="text-align:center;">@</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr>
            <td style="text-align:left;">Signet Ring (counterfeit)</td>
            <td style="text-align:right;">5sp</td>
            <td style="text-align:center;">@</td>
            <td style="text-align:left;">Difficulty 15 <i>Perception</i> to spot.</td>
        </tr>
        <tr>
            <td style="text-align:left;">Spellbook (large)</td>
            <td style="text-align:right;">100sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;">100 pages</td>
        </tr>
        <tr>
            <td style="text-align:left;">Spellbook (small)</td>
            <td style="text-align:right;">50sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;">50 pages</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Spyglass</td>
            <td style="text-align:right;">200gp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;">x2 magnification</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Tent, 2 person</td>
            <td style="text-align:right;">4sp</td>
            <td style="text-align:center;">2</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Tinder Box</td>
            <td style="text-align:right;">3sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr>
            <td style="text-align:left;">Torch</td>
            <td style="text-align:right;">1cp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;">20ft bright and 20ft dim light for 1 hour; can be used as an improvised club doing 1d6 fire damage at -1 to hit.  Roll 1d6 on each hit. On a natural 1, the torch goes out.</td>
        </tr>
        <tr>
            <td style="text-align:left;">Torch, bundle</td>
            <td style="text-align:right;">3cp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;">3 torches</td>
        </tr>
        <tr>
            <td style="text-align:left;">Vial</td>
            <td style="text-align:right;">2sp</td>
            <td style="text-align:center;">@</td>
            <td style="text-align:left;">Holds up to 1 cup of liquid</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Wood Carving Kit</td>
            <td style="text-align:right;">10sp</td>
            <td style="text-align:center;">1</td>
            <td style="text-align:left;">small woodworking tools</td>
        </tr>
        <tr style="background-color:#708090;">
            <td colspan=4>* When worn, takes up 0 slots; when carried, takes up 1.<br/># Only takes up slots in groups of 100 or more.<br/>@ Only takes up slots in groups of 10 or more.<br/><b>Splash</b> - Affects everyone within the given radius who fails a <i>Difficulty 12 Reflex Save</i>.</td>
        </tr>
    </tbody>
</table>

#### Equipment Packs
For convenience the following equipment packs exist as pre-build packages at a discount in cost for buying in ‘bulk’ during *Character Creation*.  After character creation, the items in these kits must be bought separately.

<table border=2>
    <thead>
        <tr style="background-color:#708090;">
            <th id="pack" style="text-align:left;">Pack</th>
            <th id="cost" style="text-align:right;">Cost</th>
            <th id="contents" style="text-align:left;">Contents</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="text-align:left;">Adventurer's Pack</td>
            <td style="text-align:right;">20sp</td>
            <td style="text-align:left;">backpack, bedroll, dagger, heavy cloak, mess kit, practical clothing, rations (1 week), rope (50 ft), tinderbox, torches (bundle)</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Archer's Pack</td>
            <td style="text-align:right;">120sp</td>
            <td style="text-align:left;">arrows (20), hardened leather armor, medium weapons (2), shortbow</td>
        </tr>
        <tr>
            <td style="text-align:left;">Hoplite's Pack</td>
            <td style="text-align:right;">120sp</td>
            <td style="text-align:left;">medium weapon, ringmail armor, shield</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Mage's Pack</td>
            <td style="text-align:right;">120sp</td>
            <td style="text-align:left;">a magic focus or holy symbol, candles (5), ink (vial), quills (10), spellbook</td>
        </tr>
        <tr>
            <td style="text-align:left;">Rogue's Pack</td>
            <td style="text-align:right;">70sp</td>
            <td style="text-align:left;">caltrops (bag), candles (5), crowbar, leather armor, light weapon, lockpicks, medium weapon, sack</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Skirmisher's Pack</td>
            <td style="text-align:right;">110sp</td>
            <td style="text-align:left;">buckler, candles (5), crowbar, hardened leather armor, javelins (6), light weapon, lockpicks, medium weapon</td>
        </tr>
        <tr>
            <td style="text-align:left;">Spellblade's Pack</td>
            <td style="text-align:right;">120sp</td>
            <td style="text-align:left;">a magic focus or holy symbol, buckler, ink (vial), leather armor, medium weapon, quills (10), spellbook (small)</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Trickster's Pack</td>
            <td style="text-align:right;">120sp</td>
            <td style="text-align:left;">a magic focus or holy symbol, candles (5), ink (vial), leather armor, lockpicks, medium weapon, quills (10), sack, spellbook (small)</td>
        </tr>
        <tr>
            <td style="text-align:left;">Warrior's Pack</td>
            <td style="text-align:right;">120sp</td>
            <td style="text-align:left;">heavy weapon, ringmail armor</td>
        </tr>
    </tbody>
</table>

#### Food and Shelter
While on an adventure, your character will still need food to eat and a place to sleep.  Travel rations and a thin bedroll on hard cold ground may be sustaining, but they’re hardly comfortable.  When in need of proper accommodations, the table below gives the cost for [Common](#quality) examples of the normal food and service obtainable.

<table border=2>
    <thead>
        <tr style="background-color:#708090;">
            <th id="item" style="text-align:left;">Item</th>
            <th id="cost" style="text-align:right;">Cost</th>
            <th id="notes" style="text-align:left;">Notes</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="text-align:left;">Inn Stay</td>
            <td style="text-align:right;">1sp</td>
            <td style="text-align:left;">1 day; common quality counts toward a modest Lifestyle.</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Meals</td>
            <td style="text-align:right;">1sp</td>
            <td style="text-align:left;">1 day; common quality counts toward a modest Lifestyle.</td>
        </tr>
        <tr>
            <td style="text-align:left;"><em>Drink</em></td>
            <td style="text-align:right;">--</td>
            <td style="text-align:left;">costs are per serving</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">-Ale</td>
            <td style="text-align:right;">2cp</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr>
            <td style="text-align:left;">-Beer</td>
            <td style="text-align:right;">1cp</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">-Mead</td>
            <td style="text-align:right;">2sp</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr>
            <td style="text-align:left;">-Spirits</td>
            <td style="text-align:right;">4sp</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">-Wine</td>
            <td style="text-align:right;">4cp</td>
            <td style="text-align:left;"></td>
        </tr>
    </tbody>
</table>

### Services
Below is a list of common services that an adventurer might need.  Not all services are available in every town or village.  An artisan may service multiple villages while a single city might have enough artisans to form a guild for that profession.

See the [Hirelings and Allies](HirelingsAndAlies.md) rules for additional notes on the hiring process.

<table border=2>
    <thead>
        <tr style="background-color:#708090;">
            <th id="service" style="text-align:left;">Service</th>
            <th id="cost" style="text-align:right;">Cost</th>
            <th id="notes" style="text-align:left;">Notes</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="text-align:left;"><em>Bribes</em></td>
            <td style="text-align:right;"></td>
            <td style="text-align:left;"></td>
        </tr>
        <tr>
            <td style="text-align:left;">-minor</td>
            <td style="text-align:right;">10sp</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr>
            <td style="text-align:left;">-moderate</td>
            <td style="text-align:right;">100sp</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr>
            <td style="text-align:left;">-major</td>
            <td style="text-align:right;">1,000sp</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;"><em>Coach / Cab</em></td>
            <td style="text-align:right;"></td>
            <td style="text-align:left;">In addition to the normal Quality modifiers, modifiers for route danger and providing protective services may also apply.</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">-Between Towns</td>
            <td style="text-align:right;">3cp</td>
            <td style="text-align:left;">per mile</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">-Within Town</td>
            <td style="text-align:right;">1cp</td>
            <td style="text-align:left;">for large cities, the price is per district.</td>
        </tr>
        <tr>
            <td style="text-align:left;"><em>Crimes</em></td>
            <td style="text-align:right;"></td>
            <td style="text-align:left;"></td>
        </tr>
        <tr>
            <td style="text-align:left;">-minor</td>
            <td style="text-align:right;">50sp</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr>
            <td style="text-align:left;">-major</td>
            <td style="text-align:right;">1,000sp</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr>
            <td style="text-align:left;">-capital</td>
            <td style="text-align:right;">25,000sp</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Spellcasting</td>
            <td style="text-align:right;">var</td>
            <td style="text-align:left;">100sp * (spell rank ^ 2) per casting; plus material costs.</td>
        </tr>
    </tbody>
</table>

#### Hirelings, Standard
These are the typical craftspersons and laborers that can be found in any reasonably sized town or larger community. Villages and thorps will have similar services available, at least in a nearby community.  These types of hirelings are typically employed on a daily basis (or even up to a full week).  Longer-term jobs are typically not favored by these workers for fear of backlogs with other clients.  Likewise, most won't be willing to travel more than a 1/2 day to a day from home without extra compensation (at least food, lodging and a couple extra silvers per week).  These prices on this table do not take into account any materials cost.  Material costs for new items can be estimated at 1/4 the final cost of the item.

Standard hirelings are assumed to have *Apprentice* ranking in the appropriate skills.  Hirelings of greater skill will typically cost 2 to 5 times as much.

<table border=2>
        <tr style="background-color:#708090;">
            <th id="service" style="text-align:left;"><b>Hireling</b></th>
            <th id="cost" style="text-align:right;"><b>Cost/Day</b></th>
            <th id="notes" style="text-align:left;"><b>Notes</b></th>
        </tr>
        <tr>
            <td>Animal Handler</td>
            <td align="right">1cp</td>
            <td>Can care for and train up to 4 large, 8 medium or 12 small creatures at a time.</td>
        </tr>
        <tr>
            <td style="text-align:left;">Barber</td>
            <td style="text-align:right;">1sp</td>
            <td style="text-align:left;">Basic medical services.</td>
        </tr>
        <tr>
            <td>Carpenter</td>
            <td align="right">3cp</td>
            <td>Can assist Armorers in the making of wooden shields.</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td>Cook</td>
            <td align="right">1cp</td>
            <td>Can prepare meals for up to 10 <i>Medium-Sized</i> people.</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Crafter, Other (wainwright, boatwright, cobbler, any not listed in this table)</td>
            <td style="text-align:right;">2cp</td>
            <td style="text-align:left;">More specialized or rare crafts will cost more.</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Herbalist</td>
            <td style="text-align:right;">1cp</td>
            <td style="text-align:left;">Can create 2 Healer's Kits worth of medicine per month.</td>
        </tr>
        <tr>
            <td>Laborer</td>
            <td align="right">1cp</td>
            <td>Includes bearers, porters and similar "unskilled" labor.  Can each carry 10 <i>Stowed Items</i>.</td>
        </tr>
        <tr>
            <td>Leatherer</td>
            <td align="right">2cp</td>
            <td>Can craft up to 200sp worth of Light Armor in a month.  For every 3 assistants (1cp/day/assistant), the output may be doubled.  One leatherer may benefit from no more than 6 assistants.</td>
        </tr>
        <tr>
            <td>Limner</td>
            <td align="right">10cp</td>
            <td>Paints signs and heraldic devices.</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td>Linkboy</td>
            <td align="right">1cp</td>
            <td>aka torchbearer</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td>Mason</td>
            <td align="right">4cp</td>
            <td></td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td>Pack Handler</td>
            <td align="right">2cp</td>
            <td>Knows how to load/unload pack animals.</td>
        </tr>
        <tr>
            <td>Servant</td>
            <td align="right">3cp</td>
            <td>assistant, butler, valet, etc.</td>
        </tr>
        <tr>
            <td>Tailor</td>
            <td align="right">2cp</td>
            <td></td>
        </tr>
        <tr>
            <td>Teamster</td>
            <td align="right">5cp</td>
            <td>drives carts/wagons as well as loading and unloading such</td>
        </tr>
</table>

#### Hirelings, Expert
Unlike standard hirelings, expert hirelings are in high demand and will only work on retainer.  Often the minimum contract is for a full month, if not longer.  Also, it typically takes a fair sized population to support these careers, thus these are typically only found in towns and cities.  The monthly costs on the table below include food, lodging and basic equipment.  There will be extra material costs for the construction of items.

Expert hirelings are assumed to have *Expert* ranking in the appropriate skills.  Hirelings of *Master* level skill will typically cost 3 to 10 times as much.  *Apprentice* rank hirelings cost half as much (but it may be against Guild law to hire an apprentice).

<table border=2>
    <thead>
        <tr style="background-color:#708090;">
            <th id="service" style="text-align:left;">Hireling</th>
            <th id="cost" style="text-align:right;">Cost/Day</th>
            <th id="cost" style="text-align:right;">Cost/Month</th>
            <th id="notes" style="text-align:left;">Notes</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="text-align:left;">Advocate</td>
            <td style="text-align:right;">7sp</td>
            <td style="text-align:right;">200sp</td>
            <td style="text-align:left;">Can plead with the law on a client's behalf.</td>
        </tr>
        <tr>
            <td style="text-align:left;">Alchemist</td>
            <td style="text-align:right;">20sp</td>
            <td style="text-align:right;">600sp</td>
            <td style="text-align:left;">Can create a Potion if they have the formula or a sample.  Creation from a sample takes twice as long.</td>
        </tr>
        <tr>
            <td style="text-align:left;">Apothecary</td>
            <td style="text-align:right;">10sp</td>
            <td style="text-align:right;">300sp</td>
            <td style="text-align:left;">Can create up to 5 Healer's Kits worth of medications per month.</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Armor Smith</td>
            <td style="text-align:right;">7sp</td>
            <td style="text-align:right;">200sp</td>
            <td style="text-align:left;">Can produce 1,000gp worth of Medium or Heavy Armor per month.  For every 3 assistants (30sp/month/assistant), the output may be doubled.  One armorer may benefit from no more than 6 assistants.  One armorer is required for every 50 mercenaries to maintain their armor.</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Blacksmith</td>
            <td style="text-align:right;">2sp</td>
            <td style="text-align:right;">60sp</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Bowyer</td>
            <td style="text-align:right;">4sp</td>
            <td style="text-align:right;">100sp</td>
            <td style="text-align:left;">Can create up to 400sp worth of ranged weapons and ammunition per month.  For every 3 assistants (15sp/month/assistant), the output may be doubled.  One bowyer may benefit from no more than 6 assistants. One  bowyer is required for every 50 archers to maintain their weapons and ammo.</td>
        </tr>
        <tr>
            <td style="text-align:left;">Cartographer</td>
            <td style="text-align:right;">20sp</td>
            <td style="text-align:right;">600sp</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr>
            <td style="text-align:left;">Engineer</td>
            <td style="text-align:right;">25sp</td>
            <td style="text-align:right;">750sp</td>
            <td style="text-align:left;">Required for every 100,000sp worth of construction.</td>
        </tr>
        <tr>
            <td style="text-align:left;">Interpreter</td>
            <td style="text-align:right;">10sp</td>
            <td style="text-align:right;">300sp</td>
            <td style="text-align:left;">Will know 1d3 + Rank Bonus languages</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Jeweler</td>
            <td style="text-align:right;">7sp</td>
            <td style="text-align:right;">200sp</td>
            <td style="text-align:left;">Will know 1d3 + Rank Bonus languages</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Minstrel</td>
            <td style="text-align:right;">2sp</td>
            <td style="text-align:right;">60sp</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Physic</td>
            <td style="text-align:right;">20sp</td>
            <td style="text-align:right;">600sp</td>
            <td style="text-align:left;">Expert medical service.</td>
        </tr>
        <tr>
            <td style="text-align:left;">Sage</td>
            <td style="text-align:right;">20sp</td>
            <td style="text-align:right;">600sp</td>
            <td style="text-align:left;">Additional costs per question.</td>
        </tr>
        <tr>
            <td style="text-align:left;">Scout / Guide</td>
            <td style="text-align:right;">10sp</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr>
            <td style="text-align:left;">Scribe</td>
            <td style="text-align:right;">10sp</td>
            <td style="text-align:right;">300sp</td>
            <td style="text-align:left;"></td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Spy/Assassin</td>
            <td style="text-align:right;">25sp</td>
            <td style="text-align:right;">750sp</td>
            <td style="text-align:left;">Additional costs based on mission difficulty.</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td>Steward</td>
            <td align="right">24sp</td>
            <td align="right">700sp</td>
            <td>A 7th level fighter.  Commands a fortification.  Can command 280 troops and 14 lieutenants.</td>
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="text-align:left;">Weapon Smith</td>
            <td style="text-align:right;">7sp</td>
            <td style="text-align:right;">200sp</td>
            <td style="text-align:left;">Can make up to 400sp worth of weapons per month. For every 3 assistants (30sp/month/assistant), the output may be doubled.  One weapon smith may benefit from no more than 6 assistants.  One weaponsmith is required for every 50 mercenaries to maintain their weapons.</td>
        </tr>
        <tr style="background-color:#708090;">
            <td colspan=4>Cost does not include material costs.<br/>Costs may double for hazardous / wartime duty.  Even then, most hirelings are unwilling to venture into obviously suicidal situations (like venturing into dungeons or dragon lairs.)</td>
        </tr>
    </tbody>
</table>

#### Mercenaries
Mercenaries are typically employed to guard a stronghold, encampment or similar fortified position.  The costs on the table below are for upkeep and basic equipping.  Armorer Smiths, Blacksmiths and Weapon Smiths are required to maintain the gear of your troops.

<table>
    <thead>
        <tr style="background-color:#708090;">
            <th rowspan=2 style="vertical-align:bottom;"><b>Type</b></th>
            <th align="center" rowspan=2 style="vertical-align:bottom;"><b>Level</b></th>
            <th align="center" rowspan=2 style="vertical-align:bottom;"><b>Morale</b></th>
            <th align="center" colspan=3 style="vertical-align:bottom;"><b>Cost</b></th>
            <th align="center" rowspan=2 style="vertical-align:bottom;"><b>Speed</b></th>
            <th align="center" rowspan=2 style="vertical-align:bottom;"><b>AC</b></th>
            <th align="center" rowspan=2 style="vertical-align:bottom;"><b>Attack<br/>Bonus</b></th>
            <th align="center" rowspan=2 style="vertical-align:bottom;"><b>Damage</b></th>
            <th align="center" rowspan=2 style="vertical-align:bottom;"><b>Range</b></th>
            <th align="center" colspan=3 style="vertical-align:bottom;"><b>Saving Throws</b></th>
            <th align="center" colspan=6 style="vertical-align:bottom;"><b>Abilities</b></th>
            <th align="center" rowspan=2 style="vertical-align:bottom;"><b>Notes</b></th>
        </tr>
        <tr style="background-color:#708090;">
            <th align="right" style="vertical-align:bottom;"><b>Month</b></th>
            <th align="right" style="vertical-align:bottom;"><b>Day</b></th>
            <th align="right" style="vertical-align:bottom;"><b>Equipment</b></th>
            <th align="center" style="vertical-align:bottom;"><b>E</b></th>
            <th align="center" style="vertical-align:bottom;"><b>H</b></th>
            <th align="center" style="vertical-align:bottom;"><b>S</b></th>
            <th align="center" style="vertical-align:bottom;"><b>STR</b></th>
            <th align="center" style="vertical-align:bottom;"><b>DEX</b></th>
            <th align="center" style="vertical-align:bottom;"><b>CON</b></th>
            <th align="center" style="vertical-align:bottom;"><b>INT</b></th>
            <th align="center" style="vertical-align:bottom;"><b>WIS</b></th>
            <th align="center" style="vertical-align:bottom;"><b>CHA</b></th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="vertical-align:middle;">Archer, Crossbow</td><!--Type-->
            <td style="vertical-align:middle;" align="center">0</td><!--Level-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Morale-->
            <td style="vertical-align:middle;" align="right">40sp</td><!--Cost/M-->
            <td style="vertical-align:middle;" align="right">14cp</td><!--Cost/D-->
            <td style="vertical-align:middle;" align="right">125sp</td><!--Cost/E-->
            <td style="vertical-align:middle;" align="center">30</td><!--Speed-->
            <td style="vertical-align:middle;" align="center">12 (H. Leather)</td><!--AC-->
            <td style="vertical-align:middle;" align="center">+0</td><!--AB-->
            <td style="vertical-align:middle;" align="center">1d8 (Crossbow)<br/>1d6 (LMW)</td><!--Dmg-->
            <td style="vertical-align:middle;" align="center">Far</td><!--Range-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Ev-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Ha-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Sp-->
            <td style="vertical-align:middle;" align="center">+0</td><!--STR-->
            <td style="vertical-align:middle;" align="center">+0</td><!--DEX-->
            <td style="vertical-align:middle;" align="center">+0</td><!--CON-->
            <td style="vertical-align:middle;" align="center">+0</td><!--INT-->
            <td style="vertical-align:middle;" align="center">+0</td><!--WIS-->
            <td style="vertical-align:middle;" align="center">+0</td><!--CHA-->
            <td style="vertical-align:middle;" align="left"></td><!--Notes-->
        </tr>
        <tr>
            <td style="vertical-align:middle;">Archer, Longbow</td><!--Type-->
            <td style="vertical-align:middle;" align="center">0</td><!--Level-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Morale-->
            <td style="vertical-align:middle;" align="right">80sp</td><!--Cost/M-->
            <td style="vertical-align:middle;" align="right">27cp</td><!--Cost/D-->
            <td style="vertical-align:middle;" align="right">150sp</td><!--Cost/E-->
            <td style="vertical-align:middle;" align="center">30</td><!--Speed-->
            <td style="vertical-align:middle;" align="center">12 (H. Leather)</td><!--AC-->
            <td style="vertical-align:middle;" align="center">+0</td><!--AB-->
            <td style="vertical-align:middle;" align="center">1d8 (Longbow)<br/>1d6 (LMW)</td><!--Dmg-->
            <td style="vertical-align:middle;" align="center">V. Far</td><!--Range-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Ev-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Ha-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Sp-->
            <td style="vertical-align:middle;" align="center">+0</td><!--STR-->
            <td style="vertical-align:middle;" align="center">+0</td><!--DEX-->
            <td style="vertical-align:middle;" align="center">+0</td><!--CON-->
            <td style="vertical-align:middle;" align="center">+0</td><!--INT-->
            <td style="vertical-align:middle;" align="center">+0</td><!--WIS-->
            <td style="vertical-align:middle;" align="center">+0</td><!--CHA-->
            <td style="vertical-align:middle;" align="left"></td><!--Notes-->
        </tr>
        <tr>
            <td style="vertical-align:middle;">Archer, Mounted Shortbow</td><!--Type-->
            <td style="vertical-align:middle;" align="center">0</td><!--Level-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Morale-->
            <td style="vertical-align:middle;" align="right">120sp</td><!--Cost/M-->
            <td style="vertical-align:middle;" align="right">4sp</td><!--Cost/D-->
            <td style="vertical-align:middle;" align="right">600sp</td><!--Cost/E-->
            <td style="vertical-align:middle;" align="center">80/30</td><!--Speed-->
            <td style="vertical-align:middle;" align="center">12 (H. Leather)</td><!--AC-->
            <td style="vertical-align:middle;" align="center">+0</td><!--AB-->
            <td style="vertical-align:middle;" align="center">1d6 (Shortbow)<br/>1d6 (LMW)</td><!--Dmg-->
            <td style="vertical-align:middle;" align="center">Far</td><!--Range-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Ev-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Ha-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Sp-->
            <td style="vertical-align:middle;" align="center">+0</td><!--STR-->
            <td style="vertical-align:middle;" align="center">+0</td><!--DEX-->
            <td style="vertical-align:middle;" align="center">+0</td><!--CON-->
            <td style="vertical-align:middle;" align="center">+0</td><!--INT-->
            <td style="vertical-align:middle;" align="center">+0</td><!--WIS-->
            <td style="vertical-align:middle;" align="center">+0</td><!--CHA-->
            <td style="vertical-align:middle;" align="left">Light Warhorse</td><!--Notes-->
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="vertical-align:middle;">Archer Mounted Crossbow</td><!--Type-->
            <td style="vertical-align:middle;" align="center">0</td><!--Level-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Morale-->
            <td style="vertical-align:middle;" align="right">80sp</td><!--Cost/M-->
            <td style="vertical-align:middle;" align="right">27cp</td><!--Cost/D-->
            <td style="vertical-align:middle;" align="right">625sp</td><!--Cost/E-->
            <td style="vertical-align:middle;" align="center">80/30</td><!--Speed-->
            <td style="vertical-align:middle;" align="center">12 (H. Leather)</td><!--AC-->
            <td style="vertical-align:middle;" align="center">+0</td><!--AB-->
            <td style="vertical-align:middle;" align="center">1d8 (Crossbow)<br/>1d6(LMW</td><!--Dmg-->
            <td style="vertical-align:middle;" align="center">Far</td><!--Range-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Ev-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Ha-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Sp-->
            <td style="vertical-align:middle;" align="center">+0</td><!--STR-->
            <td style="vertical-align:middle;" align="center">+0</td><!--DEX-->
            <td style="vertical-align:middle;" align="center">+0</td><!--CON-->
            <td style="vertical-align:middle;" align="center">+0</td><!--INT-->
            <td style="vertical-align:middle;" align="center">+0</td><!--WIS-->
            <td style="vertical-align:middle;" align="center">+0</td><!--CHA-->
            <td style="vertical-align:middle;" align="left">Light Warhorse</td><!--Notes-->
        </tr>
        <tr style="background-color:#91a3b0;">
           <td style="vertical-align:middle;">Archer, Shortbow</td><!--Type-->
            <td style="vertical-align:middle;" align="center">0</td><!--Level-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Morale-->
            <td style="vertical-align:middle;" align="right">40sp</td><!--Cost/M-->
            <td style="vertical-align:middle;" align="right">14cp</td><!--Cost/D-->
            <td style="vertical-align:middle;" align="right">100sp</td><!--Cost/E-->
            <td style="vertical-align:middle;" align="center">30</td><!--Speed-->
            <td style="vertical-align:middle;" align="center">12 (H. Leather)</td><!--AC-->
            <td style="vertical-align:middle;" align="center">+0</td><!--AB-->
            <td style="vertical-align:middle;" align="center">1d6 (Shortbow)<br/>1d6 (LMW)</td><!--Dmg-->
            <td style="vertical-align:middle;" align="center">Far</td><!--Range-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Ev-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Ha-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Sp-->
            <td style="vertical-align:middle;" align="center">+0</td><!--STR-->
            <td style="vertical-align:middle;" align="center">+0</td><!--DEX-->
            <td style="vertical-align:middle;" align="center">+0</td><!--CON-->
            <td style="vertical-align:middle;" align="center">+0</td><!--INT-->
            <td style="vertical-align:middle;" align="center">+0</td><!--WIS-->
            <td style="vertical-align:middle;" align="center">+0</td><!--CHA-->
            <td style="vertical-align:middle;" align="left"></td><!--Notes-->
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="vertical-align:middle;">Artillerist</td><!--Type-->
            <td style="vertical-align:middle;" align="center">0</td><!--Level-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Morale-->
            <td style="vertical-align:middle;" align="right">100sp</td><!--Cost/M-->
            <td style="vertical-align:middle;" align="right">34cp</td><!--Cost/D-->
            <td style="vertical-align:middle;" align="right">65sp</td><!--Cost/E-->
            <td style="vertical-align:middle;" align="center">30</td><!--Speed-->
            <td style="vertical-align:middle;" align="center">12 (H. Leather)</td><!--AC-->
            <td style="vertical-align:middle;" align="center">+0</td><!--AB-->
            <td style="vertical-align:middle;" align="center">1d6 (LMW)</td><!--Dmg-->
            <td style="vertical-align:middle;" align="center">Close</td><!--Range-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Ev-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Ha-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Sp-->
            <td style="vertical-align:middle;" align="center">+0</td><!--STR-->
            <td style="vertical-align:middle;" align="center">+0</td><!--DEX-->
            <td style="vertical-align:middle;" align="center">+0</td><!--CON-->
            <td style="vertical-align:middle;" align="center">+0</td><!--INT-->
            <td style="vertical-align:middle;" align="center">+0</td><!--WIS-->
            <td style="vertical-align:middle;" align="center">+0</td><!--CHA-->
            <td style="vertical-align:middle;" align="left">Required per catapult, ballista, trebuchet or the like.</td><!--Notes-->
        </tr>
        <tr>
            <td style="vertical-align:middle;">Captain</td><!--Type-->
            <td style="vertical-align:middle;" align="center">5</td><!--Level-->
            <td style="vertical-align:middle;" align="center">+3</td><!--Morale-->
            <td style="vertical-align:middle;" align="right">x20</td><!--Cost/M-->
            <td style="vertical-align:middle;" align="right">x20</td><!--Cost/D-->
            <td style="vertical-align:middle;" align="right">as troop type</td><!--Cost/E-->
            <td style="vertical-align:middle;" align="center">as troop type</td><!--Speed-->
            <td style="vertical-align:middle;" align="center">as troop type</td><!--AC-->
            <td style="vertical-align:middle;" align="center">+5</td><!--AB-->
            <td style="vertical-align:middle;" align="center">as troop type +1</td><!--Dmg-->
            <td style="vertical-align:middle;" align="center">as troop type</td><!--Range-->
            <td style="vertical-align:middle;" align="center">+4</td><!--Ev-->
            <td style="vertical-align:middle;" align="center">+5</td><!--Ha-->
            <td style="vertical-align:middle;" align="center">+4</td><!--Sp-->
            <td style="vertical-align:middle;" align="center">+1</td><!--STR-->
            <td style="vertical-align:middle;" align="center">+0</td><!--DEX-->
            <td style="vertical-align:middle;" align="center">+0</td><!--CON-->
            <td style="vertical-align:middle;" align="center">+0</td><!--INT-->
            <td style="vertical-align:middle;" align="center">+0</td><!--WIS-->
            <td style="vertical-align:middle;" align="center">+1</td><!--CHA-->
            <td style="vertical-align:middle;" align="left">May swap STR & DEX for ranged troops.<br/>May command 5 lieutenants and 100 troops.</td><!--Notes-->
        </tr>
        <tr>
            <td style="vertical-align:middle;">Cavalry, Heavy</td><!--Type-->
            <td style="vertical-align:middle;" align="center">2</td><!--Level-->
            <td style="vertical-align:middle;" align="center">+2</td><!--Morale-->
            <td style="vertical-align:middle;" align="right">120sp</td><!--Cost/M-->
            <td style="vertical-align:middle;" align="right">4sp</td><!--Cost/D-->
            <td style="vertical-align:middle;" align="right">2,680sp</td><!--Cost/E-->
            <td style="vertical-align:middle;" align="center">50/20</td><!--Speed-->
            <td style="vertical-align:middle;" align="center">17 (Chain + Shield)</td><!--AC-->
            <td style="vertical-align:middle;" align="center">+2</td><!--AB-->
            <td style="vertical-align:middle;" align="center">1d10 (lance)<br/>1d8 (a. sword)<br/>1d6 (LMW)</td><!--Dmg-->
            <td style="vertical-align:middle;" align="center">Close</td><!--Range-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Ev-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Ha-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Sp-->
            <td style="vertical-align:middle;" align="center">+0</td><!--STR-->
            <td style="vertical-align:middle;" align="center">+0</td><!--DEX-->
            <td style="vertical-align:middle;" align="center">+0</td><!--CON-->
            <td style="vertical-align:middle;" align="center">+0</td><!--INT-->
            <td style="vertical-align:middle;" align="center">+0</td><!--WIS-->
            <td style="vertical-align:middle;" align="center">+0</td><!--CHA-->
            <td style="vertical-align:middle;" align="left">Heavy Warhorse</td><!--Notes-->
        </tr>
        <tr>
            <td style="vertical-align:middle;">Cavalry, Light</td><!--Type-->
            <td style="vertical-align:middle;" align="center">0</td><!--Level-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Morale-->
            <td style="vertical-align:middle;" align="right">60sp</td><!--Cost/M-->
            <td style="vertical-align:middle;" align="right">2sp</td><!--Cost/D-->
            <td style="vertical-align:middle;" align="right">600sp</td><!--Cost/E-->
            <td style="vertical-align:middle;" align="center">80/30</td><!--Speed-->
            <td style="vertical-align:middle;" align="center">15 (H. Leather + Shield)</td><!--AC-->
            <td style="vertical-align:middle;" align="center">+0</td><!--AB-->
            <td style="vertical-align:middle;" align="center">1d10 (lance)<br/>1d6 (LMW</td><!--Dmg-->
            <td style="vertical-align:middle;" align="center">close</td><!--Range-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Ev-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Ha-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Sp-->
            <td style="vertical-align:middle;" align="center">+0</td><!--STR-->
            <td style="vertical-align:middle;" align="center">+0</td><!--DEX-->
            <td style="vertical-align:middle;" align="center">+0</td><!--CON-->
            <td style="vertical-align:middle;" align="center">+0</td><!--INT-->
            <td style="vertical-align:middle;" align="center">+0</td><!--WIS-->
            <td style="vertical-align:middle;" align="center">+0</td><!--CHA-->
            <td style="vertical-align:middle;" align="left">Light Warhorse</td><!--Notes-->
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="vertical-align:middle;">Cavalry, Medium</td><!--Type-->
            <td style="vertical-align:middle;" align="center">1</td><!--Level-->
            <td style="vertical-align:middle;" align="center">+1</td><!--Morale-->
            <td style="vertical-align:middle;" align="right">80sp</td><!--Cost/M-->
            <td style="vertical-align:middle;" align="right">27cp</td><!--Cost/D-->
            <td style="vertical-align:middle;" align="right">1,375sp</td><!--Cost/E-->
            <td style="vertical-align:middle;" align="center">60/20</td><!--Speed-->
            <td style="vertical-align:middle;" align="center">16 (Scale + Shield)</td><!--AC-->
            <td style="vertical-align:middle;" align="center">+1</td><!--AB-->
            <td style="vertical-align:middle;" align="center">1d10 (lance)<br/>1d8 (a. sword)<br/>1d6 (LMW)</td><!--Dmg-->
            <td style="vertical-align:middle;" align="center">close</td><!--Range-->
            <td style="vertical-align:middle;" align="center">+1</td><!--Ev-->
            <td style="vertical-align:middle;" align="center">+1</td><!--Ha-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Sp-->
            <td style="vertical-align:middle;" align="center">+0</td><!--STR-->
            <td style="vertical-align:middle;" align="center">+0</td><!--DEX-->
            <td style="vertical-align:middle;" align="center">+0</td><!--CON-->
            <td style="vertical-align:middle;" align="center">+0</td><!--INT-->
            <td style="vertical-align:middle;" align="center">+0</td><!--WIS-->
            <td style="vertical-align:middle;" align="center">+0</td><!--CHA-->
            <td style="vertical-align:middle;" align="left">Medium Warhorse</td><!--Notes-->
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="vertical-align:middle;">Infantry, Heavy</td><!--Type-->
            <td style="vertical-align:middle;" align="center">0</td><!--Level-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Morale-->
            <td style="vertical-align:middle;" align="right">40sp</td><!--Cost/M-->
            <td style="vertical-align:middle;" align="right">14cp</td><!--Cost/D-->
            <td style="vertical-align:middle;" align="right">350sp</td><!--Cost/E-->
            <td style="vertical-align:middle;" align="center">20</td><!--Speed-->
            <td style="vertical-align:middle;" align="center">14 (scale)</td><!--AC-->
            <td style="vertical-align:middle;" align="center">+0</td><!--AB-->
            <td style="vertical-align:middle;" align="center">1d10 (halberd)<br/>1d6 (LMW</td><!--Dmg-->
            <td style="vertical-align:middle;" align="center">close</td><!--Range-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Ev-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Ha-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Sp-->
            <td style="vertical-align:middle;" align="center">+0</td><!--STR-->
            <td style="vertical-align:middle;" align="center">+0</td><!--DEX-->
            <td style="vertical-align:middle;" align="center">+0</td><!--CON-->
            <td style="vertical-align:middle;" align="center">+0</td><!--INT-->
            <td style="vertical-align:middle;" align="center">+0</td><!--WIS-->
            <td style="vertical-align:middle;" align="center">+0</td><!--CHA-->
            <td style="vertical-align:middle;" align="left"></td><!--Notes-->
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="vertical-align:middle;">Infantry, Heavy Mounted</td><!--Type-->
            <td style="vertical-align:middle;" align="center">0</td><!--Level-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Morale-->
            <td style="vertical-align:middle;" align="right">60sp</td><!--Cost/M-->
            <td style="vertical-align:middle;" align="right">2sp</td><!--Cost/D-->
            <td style="vertical-align:middle;" align="right">850sp</td><!--Cost/E-->
            <td style="vertical-align:middle;" align="center">80/20</td><!--Speed-->
            <td style="vertical-align:middle;" align="center">14 (scale)</td><!--AC-->
            <td style="vertical-align:middle;" align="center">+0</td><!--AB-->
            <td style="vertical-align:middle;" align="center">1d10 (halberd)<br/>1d6 (LMW)</td><!--Dmg-->
            <td style="vertical-align:middle;" align="center">close</td><!--Range-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Ev-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Ha-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Sp-->
            <td style="vertical-align:middle;" align="center">+0</td><!--STR-->
            <td style="vertical-align:middle;" align="center">+0</td><!--DEX-->
            <td style="vertical-align:middle;" align="center">+0</td><!--CON-->
            <td style="vertical-align:middle;" align="center">+0</td><!--INT-->
            <td style="vertical-align:middle;" align="center">+0</td><!--WIS-->
            <td style="vertical-align:middle;" align="center">+0</td><!--CHA-->
            <td style="vertical-align:middle;" align="left">Riding Horse; dismounts before battle</td><!--Notes-->
        </tr>
        <tr>
            <td style="vertical-align:middle;">Infantry, Light</td><!--Type-->
            <td style="vertical-align:middle;" align="center">0</td><!--Level-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Morale-->
            <td style="vertical-align:middle;" align="right">20sp</td><!--Cost/M-->
            <td style="vertical-align:middle;" align="right">7cp</td><!--Cost/D-->
            <td style="vertical-align:middle;" align="right">75sp</td><!--Cost/E-->
            <td style="vertical-align:middle;" align="center">30</td><!--Speed-->
            <td style="vertical-align:middle;" align="center">15 (H Leather + Shield)</td><!--AC-->
            <td style="vertical-align:middle;" align="center">+0</td><!--AB-->
            <td style="vertical-align:middle;" align="center">1d8 (spear)<br/>1d6 (LMW)</td><!--Dmg-->
            <td style="vertical-align:middle;" align="center">close</td><!--Range-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Ev-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Ha-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Sp-->
            <td style="vertical-align:middle;" align="center">+0</td><!--STR-->
            <td style="vertical-align:middle;" align="center">+0</td><!--DEX-->
            <td style="vertical-align:middle;" align="center">+0</td><!--CON-->
            <td style="vertical-align:middle;" align="center">+0</td><!--INT-->
            <td style="vertical-align:middle;" align="center">+0</td><!--WIS-->
            <td style="vertical-align:middle;" align="center">+0</td><!--CHA-->
            <td style="vertical-align:middle;" align="left"></td><!--Notes-->
        </tr>
        <tr>
            <td style="vertical-align:middle;">Infantry, Light Mounted</td><!--Type-->
            <td style="vertical-align:middle;" align="center">0</td><!--Level-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Morale-->
            <td style="vertical-align:middle;" align="right">40sp</td><!--Cost/M-->
            <td style="vertical-align:middle;" align="right">14cp</td><!--Cost/D-->
            <td style="vertical-align:middle;" align="right">225sp</td><!--Cost/E-->
            <td style="vertical-align:middle;" align="center">80/30</td><!--Speed-->
            <td style="vertical-align:middle;" align="center">15 (H. Leather + Shield)</td><!--AC-->
            <td style="vertical-align:middle;" align="center">+0</td><!--AB-->
            <td style="vertical-align:middle;" align="center">1d8 (Spear)<br/>1d6 (LMW)</td><!--Dmg-->
            <td style="vertical-align:middle;" align="center">Close</td><!--Range-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Ev-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Ha-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Sp-->
            <td style="vertical-align:middle;" align="center">+0</td><!--STR-->
            <td style="vertical-align:middle;" align="center">+0</td><!--DEX-->
            <td style="vertical-align:middle;" align="center">+0</td><!--CON-->
            <td style="vertical-align:middle;" align="center">+0</td><!--INT-->
            <td style="vertical-align:middle;" align="center">+0</td><!--WIS-->
            <td style="vertical-align:middle;" align="center">+0</td><!--CHA-->
            <td style="vertical-align:middle;" align="left">Riding Horse; dismounts before battle</td><!--Notes-->
        </tr>
        <tr>
            <td style="vertical-align:middle;">Lieutenant</td><!--Type-->
            <td style="vertical-align:middle;" align="center">3</td><!--Level-->
            <td style="vertical-align:middle;" align="center">+2</td><!--Morale-->
            <td style="vertical-align:middle;" align="right">x10</td><!--Cost/M-->
            <td style="vertical-align:middle;" align="right">x10</td><!--Cost/D-->
            <td style="vertical-align:middle;" align="right">as troop type</td><!--Cost/E-->
            <td style="vertical-align:middle;" align="center">as troop type</td><!--Speed-->
            <td style="vertical-align:middle;" align="center">as troop type</td><!--AC-->
            <td style="vertical-align:middle;" align="center">+3</td><!--AB-->
            <td style="vertical-align:middle;" align="center">as troop type +1</td><!--Dmg-->
            <td style="vertical-align:middle;" align="center">as troop type</td><!--Range-->
            <td style="vertical-align:middle;" align="center">+2</td><!--Ev-->
            <td style="vertical-align:middle;" align="center">+4</td><!--Ha-->
            <td style="vertical-align:middle;" align="center">+2</td><!--Sp-->
            <td style="vertical-align:middle;" align="center">+1</td><!--STR-->
            <td style="vertical-align:middle;" align="center">+0</td><!--DEX-->
            <td style="vertical-align:middle;" align="center">+0</td><!--CON-->
            <td style="vertical-align:middle;" align="center">+0</td><!--INT-->
            <td style="vertical-align:middle;" align="center">+0</td><!--WIS-->
            <td style="vertical-align:middle;" align="center">+1</td><!--CHA-->
            <td style="vertical-align:middle;" align="left">May swap STR & DEX for ranged troops.<br/>May command 3 Sergeants and 30 troops.</td><!--Notes-->
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="vertical-align:middle;">Militia</td><!--Type-->
            <td style="vertical-align:middle;" align="center">0</td><!--Level-->
            <td style="vertical-align:middle;" align="center">-1</td><!--Morale-->
            <td style="vertical-align:middle;" align="right">10sp</td><!--Cost/M-->
            <td style="vertical-align:middle;" align="right">4cp</td><!--Cost/D-->
            <td style="vertical-align:middle;" align="right">10sp</td><!--Cost/E-->
            <td style="vertical-align:middle;" align="center">40</td><!--Speed-->
            <td style="vertical-align:middle;" align="center">10 (none)</td><!--AC-->
            <td style="vertical-align:middle;" align="center">+0</td><!--AB-->
            <td style="vertical-align:middle;" align="center">1d6 (improvised)</td><!--Dmg-->
            <td style="vertical-align:middle;" align="center">close</td><!--Range-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Ev-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Ha-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Sp-->
            <td style="vertical-align:middle;" align="center">+0</td><!--STR-->
            <td style="vertical-align:middle;" align="center">+0</td><!--DEX-->
            <td style="vertical-align:middle;" align="center">+0</td><!--CON-->
            <td style="vertical-align:middle;" align="center">+0</td><!--INT-->
            <td style="vertical-align:middle;" align="center">+0</td><!--WIS-->
            <td style="vertical-align:middle;" align="center">+0</td><!--CHA-->
            <td style="vertical-align:middle;" align="left"></td><!--Notes-->
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="vertical-align:middle;">Pike</td><!--Type-->
            <td style="vertical-align:middle;" align="center">0</td><!--Level-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Morale-->
            <td style="vertical-align:middle;" align="right">60sp</td><!--Cost/M-->
            <td style="vertical-align:middle;" align="right">2sp</td><!--Cost/D-->
            <td style="vertical-align:middle;" align="right">330sp</td><!--Cost/E-->
            <td style="vertical-align:middle;" align="center">20</td><!--Speed-->
            <td style="vertical-align:middle;" align="center">14 (Scale)</td><!--AC-->
            <td style="vertical-align:middle;" align="center">+0</td><!--AB-->
            <td style="vertical-align:middle;" align="center">1d10 (Pike)<br/>1d6 (LMW)</td><!--Dmg-->
            <td style="vertical-align:middle;" align="center">Close</td><!--Range-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Ev-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Ha-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Sp-->
            <td style="vertical-align:middle;" align="center">+0</td><!--STR-->
            <td style="vertical-align:middle;" align="center">+0</td><!--DEX-->
            <td style="vertical-align:middle;" align="center">+0</td><!--CON-->
            <td style="vertical-align:middle;" align="center">+0</td><!--INT-->
            <td style="vertical-align:middle;" align="center">+0</td><!--WIS-->
            <td style="vertical-align:middle;" align="center">+0</td><!--CHA-->
            <td style="vertical-align:middle;" align="left"></td><!--Notes-->
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="vertical-align:middle;">Sapper</td><!--Type-->
            <td style="vertical-align:middle;" align="center">0</td><!--Level-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Morale-->
            <td style="vertical-align:middle;" align="right">80sp</td><!--Cost/M-->
            <td style="vertical-align:middle;" align="right">27cp</td><!--Cost/D-->
            <td style="vertical-align:middle;" align="right">55sp</td><!--Cost/E-->
            <td style="vertical-align:middle;" align="center">30</td><!--Speed-->
            <td style="vertical-align:middle;" align="center">12 (H. Leather)</td><!--AC-->
            <td style="vertical-align:middle;" align="center">+0</td><!--AB-->
            <td style="vertical-align:middle;" align="center">1d6 (LMW)</td><!--Dmg-->
            <td style="vertical-align:middle;" align="center">close</td><!--Range-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Ev-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Ha-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Sp-->
            <td style="vertical-align:middle;" align="center">+0</td><!--STR-->
            <td style="vertical-align:middle;" align="center">+0</td><!--DEX-->
            <td style="vertical-align:middle;" align="center">+0</td><!--CON-->
            <td style="vertical-align:middle;" align="center">+0</td><!--INT-->
            <td style="vertical-align:middle;" align="center">+0</td><!--WIS-->
            <td style="vertical-align:middle;" align="center">+0</td><!--CHA-->
            <td style="vertical-align:middle;" align="left">Required per non-ranged siege weapons and to supervise tunneling.</td><!--Notes-->
        </tr>
        <tr>
            <td style="vertical-align:middle;">Sergeant</td><!--Type-->
            <td style="vertical-align:middle;" align="center">1</td><!--Level-->
            <td style="vertical-align:middle;" align="center">+1</td><!--Morale-->
            <td style="vertical-align:middle;" align="right">x5</td><!--Cost/M-->
            <td style="vertical-align:middle;" align="right">x5</td><!--Cost/D-->
            <td style="vertical-align:middle;" align="right">as troop type</td><!--Cost/E-->
            <td style="vertical-align:middle;" align="center">as troop type</td><!--Speed-->
            <td style="vertical-align:middle;" align="center">as troop type</td><!--AC-->
            <td style="vertical-align:middle;" align="center">+1</td><!--AB-->
            <td style="vertical-align:middle;" align="center">as troop type</td><!--Dmg-->
            <td style="vertical-align:middle;" align="center">as troop type</td><!--Range-->
            <td style="vertical-align:middle;" align="center">+1</td><!--Ev-->
            <td style="vertical-align:middle;" align="center">+1</td><!--Ha-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Sp-->
            <td style="vertical-align:middle;" align="center">+0</td><!--STR-->
            <td style="vertical-align:middle;" align="center">+0</td><!--DEX-->
            <td style="vertical-align:middle;" align="center">+0</td><!--CON-->
            <td style="vertical-align:middle;" align="center">+0</td><!--INT-->
            <td style="vertical-align:middle;" align="center">+0</td><!--WIS-->
            <td style="vertical-align:middle;" align="center">+0</td><!--CHA-->
            <td style="vertical-align:middle;" align="left">Can lead 10 troops</td><!--Notes-->
        </tr>
        <tr>
            <td style="vertical-align:middle;">Slinger</td><!--Type-->
            <td style="vertical-align:middle;" align="center">0</td><!--Level-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Morale-->
            <td style="vertical-align:middle;" align="right">60sp</td><!--Cost/M-->
            <td style="vertical-align:middle;" align="right">2sp</td><!--Cost/D-->
            <td style="vertical-align:middle;" align="right">60sp</td><!--Cost/E-->
            <td style="vertical-align:middle;" align="center">30</td><!--Speed-->
            <td style="vertical-align:middle;" align="center">14 (H. Leather + Buckler)</td><!--AC-->
            <td style="vertical-align:middle;" align="center">+0</td><!--AB-->
            <td style="vertical-align:middle;" align="center">1d6 (Sling)<br/>1d6 (LMW)</td><!--Dmg-->
            <td style="vertical-align:middle;" align="center">Far</td><!--Range-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Ev-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Ha-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Sp-->
            <td style="vertical-align:middle;" align="center">+0</td><!--STR-->
            <td style="vertical-align:middle;" align="center">+0</td><!--DEX-->
            <td style="vertical-align:middle;" align="center">+0</td><!--CON-->
            <td style="vertical-align:middle;" align="center">+0</td><!--INT-->
            <td style="vertical-align:middle;" align="center">+0</td><!--WIS-->
            <td style="vertical-align:middle;" align="center">+0</td><!--CHA-->
            <td style="vertical-align:middle;" align="left"></td><!--Notes-->
        </tr>
        <tr style="background-color:#708090;">
            <td colspan=21>Pay rate for leaders is a multiplier of the base troop type (for example, a Heavy Infantry Lieutenant costs 400sp per month).<br/>LMW = Light Melee Weapon<br/>Daily cost is doubled for hazardous/wartime duty.  Even so, will not venture into obvious suicide (like monster lairs and dungeons).</td>
        </tr>
    </tbody>
</table>

#### Ship's Crew
The number of crew required to operate and maintain a ship will depend on the size of the ship.  No matter the size, a Ship's Captain will be required, though a sufficiently experienced and capable PC can potentially act in that role.

<table>
    <thead>
        <tr style="background-color:#708090;">
            <th rowspan=2 style="vertical-align:bottom;"><b>Type</b></th>
            <th align="center" rowspan=2 style="vertical-align:bottom;"><b>Level</b></th>
            <th align="center" rowspan=2 style="vertical-align:bottom;"><b>Morale</b></th>
            <th align="center" colspan=3 style="vertical-align:bottom;"><b>Cost</b></th>
            <th align="center" rowspan=2 style="vertical-align:bottom;"><b>Speed</b></th>
            <th align="center" rowspan=2 style="vertical-align:bottom;"><b>AC</b></th>
            <th align="center" rowspan=2 style="vertical-align:bottom;"><b>Attack<br/>Bonus</b></th>
            <th align="center" rowspan=2 style="vertical-align:bottom;"><b>Damage</b></th>
            <th align="center" rowspan=2 style="vertical-align:bottom;"><b>Range</b></th>
            <th align="center" colspan=3 style="vertical-align:bottom;"><b>Saving Throws</b></th>
            <th align="center" colspan=6 style="vertical-align:bottom;"><b>Abilities</b></th>
            <th align="center" rowspan=2 style="vertical-align:bottom;"><b>Notes</b></th>
        </tr>
        <tr style="background-color:#708090;">
            <th align="right" style="vertical-align:bottom;"><b>Month</b></th>
            <th align="right" style="vertical-align:bottom;"><b>Day</b></th>
            <th align="right" style="vertical-align:bottom;"><b>Equipment</b></th>
            <th align="center" style="vertical-align:bottom;"><b>E</b></th>
            <th align="center" style="vertical-align:bottom;"><b>H</b></th>
            <th align="center" style="vertical-align:bottom;"><b>S</b></th>
            <th align="center" style="vertical-align:bottom;"><b>STR</b></th>
            <th align="center" style="vertical-align:bottom;"><b>DEX</b></th>
            <th align="center" style="vertical-align:bottom;"><b>CON</b></th>
            <th align="center" style="vertical-align:bottom;"><b>INT</b></th>
            <th align="center" style="vertical-align:bottom;"><b>WIS</b></th>
            <th align="center" style="vertical-align:bottom;"><b>CHA</b></th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="vertical-align:middle;">Marine</td><!--Type-->
            <td style="vertical-align:middle;" align="center">0</td><!--Level-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Morale-->
            <td style="vertical-align:middle;" align="right">60sp</td><!--Cost/M-->
            <td style="vertical-align:middle;" align="right">2sp</td><!--Cost/D-->
            <td style="vertical-align:middle;" align="right">135sp</td><!--Cost/E-->
            <td style="vertical-align:middle;" align="center">20</td><!--Speed-->
            <td style="vertical-align:middle;" align="center">15 (Ringmail + Shield)</td><!--AC-->
            <td style="vertical-align:middle;" align="center">+0</td><!--AB-->
            <td style="vertical-align:middle;" align="center">1d8 (Spear)<br/>1d6 (LMW)<!--Dmg-->
            <td style="vertical-align:middle;" align="center">Close</td><!--Range-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Ev-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Ha-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Sp-->
            <td style="vertical-align:middle;" align="center">+0</td><!--STR-->
            <td style="vertical-align:middle;" align="center">+0</td><!--DEX-->
            <td style="vertical-align:middle;" align="center">+0</td><!--CON-->
            <td style="vertical-align:middle;" align="center">+0</td><!--INT-->
            <td style="vertical-align:middle;" align="center">+0</td><!--WIS-->
            <td style="vertical-align:middle;" align="center">+0</td><!--CHA-->
            <td style="vertical-align:middle;" align="left"></td><!--Notes-->
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="vertical-align:middle;">Rower</td><!--Type-->
            <td style="vertical-align:middle;" align="center">0</td><!--Level-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Morale-->
            <td style="vertical-align:middle;" align="right">100sp</td><!--Cost/M-->
            <td style="vertical-align:middle;" align="right">34cp</td><!--Cost/D-->
            <td style="vertical-align:middle;" align="right">60sp</td><!--Cost/E-->
            <td style="vertical-align:middle;" align="center">30</td><!--Speed-->
            <td style="vertical-align:middle;" align="center">14 (H. Leather + Buckler)</td><!--AC-->
            <td style="vertical-align:middle;" align="center">+0</td><!--AB-->
            <td style="vertical-align:middle;" align="center">1d6 (LMW)<!--Dmg-->
            <td style="vertical-align:middle;" align="center">Close</td><!--Range-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Ev-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Ha-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Sp-->
            <td style="vertical-align:middle;" align="center">+0</td><!--STR-->
            <td style="vertical-align:middle;" align="center">+0</td><!--DEX-->
            <td style="vertical-align:middle;" align="center">+0</td><!--CON-->
            <td style="vertical-align:middle;" align="center">+0</td><!--INT-->
            <td style="vertical-align:middle;" align="center">+0</td><!--WIS-->
            <td style="vertical-align:middle;" align="center">+0</td><!--CHA-->
            <td style="vertical-align:middle;" align="left"></td><!--Notes-->
        </tr>
        <tr>
            <td style="vertical-align:middle;">Sailor</td><!--Type-->
            <td style="vertical-align:middle;" align="center">0</td><!--Level-->
            <td style="vertical-align:middle;" align="center">-1</td><!--Morale-->
            <td style="vertical-align:middle;" align="right">40sp</td><!--Cost/M-->
            <td style="vertical-align:middle;" align="right">14cp</td><!--Cost/D-->
            <td style="vertical-align:middle;" align="right">20sp</td><!--Cost/E-->
            <td style="vertical-align:middle;" align="center">40</td><!--Speed-->
            <td style="vertical-align:middle;" align="center">13 (Buckler)</td><!--AC-->
            <td style="vertical-align:middle;" align="center">+0</td><!--AB-->
            <td style="vertical-align:middle;" align="center">1d6 (LMW)<!--Dmg-->
            <td style="vertical-align:middle;" align="center">Close</td><!--Range-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Ev-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Ha-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Sp-->
            <td style="vertical-align:middle;" align="center">+0</td><!--STR-->
            <td style="vertical-align:middle;" align="center">+0</td><!--DEX-->
            <td style="vertical-align:middle;" align="center">+0</td><!--CON-->
            <td style="vertical-align:middle;" align="center">+0</td><!--INT-->
            <td style="vertical-align:middle;" align="center">+0</td><!--WIS-->
            <td style="vertical-align:middle;" align="center">+0</td><!--CHA-->
            <td style="vertical-align:middle;" align="left"></td><!--Notes-->
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="vertical-align:middle;">Ship's Captain</td><!--Type-->
            <td style="vertical-align:middle;" align="center">5</td><!--Level-->
            <td style="vertical-align:middle;" align="center">+3</td><!--Morale-->
            <td style="vertical-align:middle;" align="right">x20</td><!--Cost/M-->
            <td style="vertical-align:middle;" align="right">x20</td><!--Cost/D-->
            <td style="vertical-align:middle;" align="right">as troop type</td><!--Cost/E-->
            <td style="vertical-align:middle;" align="center">as troop type</td><!--Speed-->
            <td style="vertical-align:middle;" align="center">as troop type</td><!--AC-->
            <td style="vertical-align:middle;" align="center">+5</td><!--AB-->
            <td style="vertical-align:middle;" align="center">as troop type +1<!--Dmg-->
            <td style="vertical-align:middle;" align="center">as troop type</td><!--Range-->
            <td style="vertical-align:middle;" align="center">+4</td><!--Ev-->
            <td style="vertical-align:middle;" align="center">+5</td><!--Ha-->
            <td style="vertical-align:middle;" align="center">+4</td><!--Sp-->
            <td style="vertical-align:middle;" align="center">+1</td><!--STR-->
            <td style="vertical-align:middle;" align="center">+0</td><!--DEX-->
            <td style="vertical-align:middle;" align="center">+0</td><!--CON-->
            <td style="vertical-align:middle;" align="center">+0</td><!--INT-->
            <td style="vertical-align:middle;" align="center">+0</td><!--WIS-->
            <td style="vertical-align:middle;" align="center">+1</td><!--CHA-->
            <td style="vertical-align:middle;" align="left">Required per ship.</td><!--Notes-->
        </tr>
        <tr>
            <td style="vertical-align:middle;">Ship's Lieutenant</td><!--Type-->
            <td style="vertical-align:middle;" align="center">3</td><!--Level-->
            <td style="vertical-align:middle;" align="center">+2</td><!--Morale-->
            <td style="vertical-align:middle;" align="right">x10</td><!--Cost/M-->
            <td style="vertical-align:middle;" align="right">x10</td><!--Cost/D-->
            <td style="vertical-align:middle;" align="right">as troop type</td><!--Cost/E-->
            <td style="vertical-align:middle;" align="center">as troop type</td><!--Speed-->
            <td style="vertical-align:middle;" align="center">as troop type</td><!--AC-->
            <td style="vertical-align:middle;" align="center">+2</td><!--AB-->
            <td style="vertical-align:middle;" align="center">as troop type +1<!--Dmg-->
            <td style="vertical-align:middle;" align="center">as troop type</td><!--Range-->
            <td style="vertical-align:middle;" align="center">+2</td><!--Ev-->
            <td style="vertical-align:middle;" align="center">+4</td><!--Ha-->
            <td style="vertical-align:middle;" align="center">+2</td><!--Sp-->
            <td style="vertical-align:middle;" align="center">+1</td><!--STR-->
            <td style="vertical-align:middle;" align="center">+0</td><!--DEX-->
            <td style="vertical-align:middle;" align="center">+0</td><!--CON-->
            <td style="vertical-align:middle;" align="center">+0</td><!--INT-->
            <td style="vertical-align:middle;" align="center">+0</td><!--WIS-->
            <td style="vertical-align:middle;" align="center">+1</td><!--CHA-->
            <td style="vertical-align:middle;" align="left">Required per 20 crew.</td><!--Notes-->
        </tr>
        <tr style="background-color:#91a3b0;">
            <td style="vertical-align:middle;">Ship's Mate</td><!--Type-->
            <td style="vertical-align:middle;" align="center">1</td><!--Level-->
            <td style="vertical-align:middle;" align="center">+1</td><!--Morale-->
            <td style="vertical-align:middle;" align="right">x5</td><!--Cost/M-->
            <td style="vertical-align:middle;" align="right">x5</td><!--Cost/D-->
            <td style="vertical-align:middle;" align="right">as troop type</td><!--Cost/E-->
            <td style="vertical-align:middle;" align="center">as troop type</td><!--Speed-->
            <td style="vertical-align:middle;" align="center">as troop type</td><!--AC-->
            <td style="vertical-align:middle;" align="center">+1</td><!--AB-->
            <td style="vertical-align:middle;" align="center">as troop type<!--Dmg-->
            <td style="vertical-align:middle;" align="center">as troop type</td><!--Range-->
            <td style="vertical-align:middle;" align="center">+1</td><!--Ev-->
            <td style="vertical-align:middle;" align="center">+1</td><!--Ha-->
            <td style="vertical-align:middle;" align="center">+0</td><!--Sp-->
            <td style="vertical-align:middle;" align="center">+0</td><!--STR-->
            <td style="vertical-align:middle;" align="center">+0</td><!--DEX-->
            <td style="vertical-align:middle;" align="center">+0</td><!--CON-->
            <td style="vertical-align:middle;" align="center">+0</td><!--INT-->
            <td style="vertical-align:middle;" align="center">+0</td><!--WIS-->
            <td style="vertical-align:middle;" align="center">+0</td><!--CHA-->
            <td style="vertical-align:middle;" align="left">Required per 10 crew.</td><!--Notes-->
        </tr>
        <tr style="background-color:#708090;">
            <td colspan=21>Pay rate for leaders is a multiplier of the base troop type (for example, a Heavy Infantry Lieutenant costs 400sp per month).<br/>LMW = Light Melee Weapon<br/>Daily cost is doubled for hazardous/wartime duty.  Even so, will not venture into obvious suicide (like monster lairs and dungeons).</td>
        </tr>
    </tbody>
</table>

#### Mounts, Livestock and Transport
Be it as a beast of burden, means of transportation or just some extra protection and companionship, a well-trained animal can be a valuable asset.  The speed given in the table below is the animal’s combat speed.  The carry value is the encumbrance value worth of gear an animal can carry.  A rider typically counts as 3 encumbrance for small creatures, 6 for medium and 10 or more for large creatures.  Also take into account the gear the rider is wearing and carrying.

Animals can typically drag/pull five times their carry if otherwise unburdened.

| Animal             |    Cost | Speed | Notes |
|:-------------------|--------:|:-----:|:------|
| Camel              |   100sp | 50ft  | Carry 30 items |
| Donkey / Mule      |    50sp | 40ft  | Carry 20 items |
| Horse, draft / Ox  |   100sp | 40ft  | Carry 45 items |
| Horse, riding      |   150sp | 60ft  | Carry 30 items |
| Horse, heavy war   | 2,000sp | 60ft  | Carry 40 items |
| Horse, light war   |   500sp | 60ft  | Carry 30 items |
| Horse, med. war    | 1,000sp | 60ft  | Carry 35 items |
| Dog, hunting/guard |    25sp | 60ft  | Carry 5 items |
| Dog, war           |    50sp | 40ft  | Carry 10 items |
| Pony               |    60sp | 40ft  | Carry 15 items |

#### Tack and Harness
Once you have an animal companion, you way want to outfit it for your adventuring lifestyle.  The Barding entry of the table gives the cost and encumbrance multipliers for barding equivalent to any of the armor types listed above.

| Item             |  Cost | Slots | Notes |
|:-----------------|------:|:-----:|:------|
| *Barding*        |       |       |  |
| -Small           |  x0.5 | x0.5  |  |
| -Medium          |  x1.0 | x1.0  |  |
| -Large           |  x4.0 | x2.0  |  |
| -Huge            |  x8.0 | x4.0  |  |
| Bit & Bridle     |   4sp |    @  | **Disadvantage** on mount control checks without this. |
| Feed (dialy)     |   1cp |    2  |  |
| *Saddle*         |       |       | **Disadvantage** on riding checks without this. |
| -Exotic          | 120sp |    8  | Required for aquatic or flying mounts. |
| -Military        |  40sp |    6  | Grants **Advantage** on checks to remain mounted. |
| -Pack            |  10sp |    3  | Increases carry capacity by 20%. |
| -Riding          |  20sp |    5  |  |
| Saddlebags       |   8sp |    2  | Increase carry capacity by 10%. |
| Stabling (daily) |   1sp |   --  | Includes straw to eat, access to the water trough and a brush down by a stable hand. |

<sub>
@ No encumbrance when worn.  Encumbrance 1 otherwise.
</sub>

#### Drawn Vehicles
Sometimes you want to travel in style.  The prices below are to outright own a given vehicle.  The temporary loan of a vehicle is typically 10% of the cost per day, with 1/4 to 1/2 the purchase cost as a down payment.

Encumbrance is in **Slots** when the vehicle is being pulled and does not account for items in the vehicle.  A drawn vehicle's max capacity is equal to its own Encumbrance.

|  Vehicle   |   Cost  |  Speed  |  Min Animals                    |  Load                        |
|:-----------|--------:|:-------:|:--------------------------------|:-----------------------------|
|  Carriage  |  500sp  |   30    |  1 draft horse<br/>or 2 mules   |  4 passengers plus 20 slots  |
|  Cart      |   16sp  |   20    |  1 draft horse<br/>or 2 mules   |  40 slots                    |
|  Chariot   |  200sp  |   40    |  1 riding horse                 |  1 passenger plus 10 slots   |
|  Wagon     |   50sp  |   20    |  2 draft horses<br/>or 4 mules  |  150 slots                   |  

<sub>Doubling the number of animals doubles the vehicles capacity.</sub>
<sub>These vehicles may not traverse difficult terrain except by well-maintained roads.</sub>