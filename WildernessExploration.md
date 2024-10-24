# Wilderness Exploration
- [Wilderness Exploration Turn Sequence](#Wilderness%20Exploration%20Turn%20Sequence)
- [Time](#Time)
- [Well-Traveled Routes](#Well-Traveled%20Routes)
- [Getting Lost](#Getting%20Lost)
- [Travel Speed](#Travel%20Speed)
	- [Travel Speed Chart](#Travel%20Speed%20Chart)
	- [Terrain](#Terrain)
	- [Forced March](#Forced%20March)
	- [Double-Time](#Double-Time)
	- [Resting](#Resting)
- [Foraging and Hunting](#Foraging%20and%20Hunting)
- [Visibility](#Visibility)
- [Random Encounters](#Random%20Encounters)
- [Evasion and Pursuit](#Evasion%20and%20Pursuit)
	- [Pursuit](#Pursuit)

## Wilderness Exploration Turn Sequence
1. Decide Direction: The party decides the direction they will travel for the next Watch.
2. Getting Lost: The GM rolls for the party getting lost.
3. Random Encounters: The GM makes checks as needed.
4. Description: The GM describes what the party encounters (terrain passed through, landmarks other points of interest).  The GM also asks the players for their actions as needed.  If other creatures are encountered, follow the procedure outlined in the Encounter rules.
5. End of Watch: The GM performs any needed record keeping: rations, fatigue, spell durations, etc.

## Time
If the journey will take a day or less, time can be tracked in Hours or Watches.<br/>
If the journey will take a week or less, time can be tracked in Watches or Days.<br/>
If the journey will take more than a week, time should be tracked in Days or Weeks.<br/>
See also [Time](RulesSynopsis.md#Time) in the Rules Synopsis document.

## Well-Traveled Routes
If the party is traveling in well-known lands along a known route, there is no chance of their getting lost barring supernatural effects.

## Getting Lost
With a river, road or similar land-feature to follow, there is no chance of a party getting lost in the wilderness.  When travelling cross-country without such an aid, the GM should make a **Wisdom** check for the character best suited to wilderness exploration.  The character's **skill bonus** should be taken into account if they have an appropriate **background profession** (such as ranger/forester or hunter).  The **DT** of the check depends on the terrain being traveled:
- Clear with many landmarks: 9+
- Obscured or few landmarks (hills, forest, etc): 12+
- Heavily obscured or obscured with few landmarks (jungle, swamp, desert, ice fields): 15+

If this check is failed, the party will lose their way but will likely not know it.  In this case, the direction of travel is determined randomly.  The results on the table below are relative to the desired direction of travel.

| d10 | Direction          |
|:---:|:-------------------|
| 1-3 | Angled Left        |
| 4-6 | Angled Right       |
| 7-8 | In Circles         |
|  9  | Opposite Direction |
| 10  | Desired Direction  |

## Travel Speed
When travelling overland, characters can travel their [Exploration Speed](Dungeoneering.md#exploration%20speed) divided by five in miles per day.  Use the chart below for quick reference:

### Travel Speed Chart
| Base Move | Hour  | Watch  | Day  |
|:---------:|:-----:|-------:|:----:|
| 20ft      | 1.5ml |  6.0ml | 12ml |
| 25ft      | 1.9ml |  7.5ml | 15ml |
| 30ft      | 2.3ml |  9.0ml | 18ml |
| 35ft      | 2.6ml | 10.5ml | 21ml |
| 40ft      | 3.0ml | 12.0ml | 24ml |
| 45ft      | 3.4ml | 13.5ml | 27ml |
| 50ft      | 3.8ml | 10.0ml | 30ml |

### Terrain
Different types of terrain will modify the speed at which the party travels.
- **Rough (desert, forest, hills, etc):** 2/3 speed
- **Very Rough (jungle, mountain, swamp, etc):** 1/2 speed
- **Easy (well maintained roads):** 1.5x speed

Flying creatures ignore terrain penalties.

### Forced March
The above rules assume roughly 8 hours of travel with regular breaks for rest and food each day.  If needed, a party may perform a **Forced March** to travel further.  Forced Marches are always measured in hours (after 2 full [Watches](RulesSynopsis.md#time) of travel).  At the end of each hour, every member of the party must make an [Exhaustion Check](CoreRules.md#exhaustion) vs **DT 12** (+3 per additional hour after the first) or gain a level of [Exhaustion](Combat.md#Exhaustion).

### Double-Time
Another way to increase the rate of travel is to march at "double-time".  This increases the party's speed by 50%, but an [Exhaustion Check](CoreRules.md#exhaustion) must be made at the end of each hour of double-time movement.  This check is vs **DT 12** + 3 per consecutive hour.  If the check is failed, that party member gains a level of [Exhaustion](Combat.md#Exhaustion).  Anyone with any levels of **Exhaustion** may not march at double-time.

### Resting
For every 6 days of travel, one must be spent resting.  If the party forgoes this rest period, each party member must make an [Exhaustion Check](CoreRules.md#exhaustion) vs a **DT 12** + 3 per consecutive day of travel or gain a level of [Exhaustion](Combat.md#Exhaustion).  This is on top of any other checks for **Forced Marches** and **Double-Time**.

## Foraging and Hunting
During travel, the party may make a Skilled Wisdom check to find enough food for 1d6 characters.  This may not be done during a **Forced March** or **Double-Time** movement.

## Visibility
On open and flat terrain, the party can typically see for about 3 miles in any direction.  [Obscured](#getting%20lost) terrain reduces this to 2 miles and Heavily Obscured terrain reduces to 1 mile or less.  Elevation can increase this distance.  [Here](https://www.starpath.com/calc/Distance%20Calculators/horizon.html) is a useful tool for calculating the horizon distance.

## Random Encounters
**Frequency:** Normally, in well settled/populated areas, random encounters should be check for 3 or 4 times per day (typically once per Watch).  In sparsely populated areas, the frequency of the check can be as low as once per day.

**Chance:** Normal odds for most wilderness areas should be 1 in 6 and could go as high as 3 in 6 for wild and untamed areas.

**Distance:** The source of the encounter will be 4d6x10 yards away.  If either side is surprised, reduce this distance to 1d4x10 yards.  Roll 1d6 to determine the encounter's direction of travel (if any):
- 1-3: moving toward the party
- 4-5: moving away from the party
- 6: stationary

## Evasion and Pursuit
In dense terrain (jungle, swamp, etc) follow the [Evasion and Pursuit](Dungeoneering.md#evasin%20and%20pursuit) rules under Dungeoneering.

In open terrain (such as plains, hills, sparse forest, etc) follow this procedure:
- If one side has the advantage of [Surprise](Combat.md#suprise), it may automatically flee without the other side getting the chance to pursue (they may not event be aware of the fleeing side).
- If no one has the Surprise advantage, compare the size of the two groups to determine the chance of escape.

If one group attempts to evade the other, the evading group makes a contested Stealth check vs the other side's Perception.  If the evading side wins, they get away without issue.  Otherwise the Pursuit rules will come into play.

The following factors will modify this contested roll as follows:
- If the group is 5 or fewer in number, they roll with Advantage.
- If the group is 13 or more in number, they roll with Disadvantage.
- If one side is at least twice as fast at the other, they roll with Advantage.
- If the terrain is obscuring and the pursuing side is not intimately familiar with the territory, the pursuing side rolls with Disadvantage.

### Pursuit
Wilderness pursuit is typically tracked in [Watches](Combat.md#Time) or [Hours](Combat.md#time).

1. The fleeing side will flee in a random direction if they do not follow easy to see landmarks.  Note that if the group does decide to follow a landmark, this may make it easier for the pursuers to follow.
2. If the pursuing group has a greater movement rate than the fleeing side, the pursuing side makes its pursuit roll with Advantage.
3. Both sides make a contested D20 Wisdom roll. Add skill bonuses if the group has someone trained in hunting/tracking/survival/etc.  Compare the results on the table below:

| Group | Result | Outcome |
|:------|:-------|:--------|
| Evaders  | Win by 10+ | The evaders get away clean. |
| Evaders  | Win by 5-9 | The evaders gain Advantage on their next roll. |
| Evaders  | Win by 0-4 | Neither side gains or loses ground. |
| Pursuers | Win by 1-4 | Neither side gains or loses ground. |
| Pursuers | Win by 5-9 | The pursuers gain Advantage on their next roll. |
| Pursuers | Win by 10+ | The pursuers intercept the evaders. |

At the end of each time increment, the members of both parties must make an [Exhaustion check](CoreRules.md#Exhaustion) or gain one level of [Exhaustion](Combat.md#exhaustion).  Unlike in the [Dungeoneering](Dungeoneering.md#evasion%20and%20pursuit) rules (where characters are running full speed), gaining levels of Exhaustion does not stop either side, but the new movement rates and check penalties will need to be applied.