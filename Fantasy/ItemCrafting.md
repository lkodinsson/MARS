# Item Crafting

* [Normal Item Crafting](#normal-item-crafting)
* [Upgrading Items](#upgrading-items)
* [Bulk Crafting](#bulk-crafting)
* [Long-term Crafting](#long-term-crafting)
* [Rushed Crafting](#rushed-crafting)
* [Magic Item Crafting](#magic-item-crafting)
* [Base Magic Cost](#base-magic-cost)
* [Scrolls](#scrolls)
* [Limited Use Items](#limited-use-items)
* [Multiple Use Items](#multiple-use-items)
* [Continuous Use Items](#continuous-use-items)
* [Multiple Effects](#multiple-effects)
* [Triggered Effects](#triggered-effects)
* [Curses](#curses)
* [Magic Stabilization](#magic-stabilization)
* [Charge Bonding](#charge-bonding)
* [Mana Focusing](#mana-focusing)

Click [here](/Fantasy/MagicEquipment.md) for examples of low cost magic equipment, or [here](/Fantasy/ArtifactEquipment.md) for examples of high cost magic equipment.

## Normal Item Crafting

The first step to crafting an item is just a matter of roleplaying: is a workshop or marketplace available, or do you carry the tools and materials necessary to build this item? Afterwards, there are three basic steps:

* Determine the total cost and craft difficulty
* Roll a craft check
* Determine craft progress and pay the immediate cost

The difficulty value to craft an item is based on its cost. This can be determined manually by finding the square root of the cost in silver pieces (rounded down), then adding 4 to the result. The following table can be used as a quick reference:

##### Table: Item Cost vs Craft Difficulty
| Item Cost | Difficulty | Item Cost | Difficulty |
|:-:|:-:|:-:|:-:|
| 1sp+ | 5 | 361sp+ | 23 |
| 4sp+ | 6 | 400sp+ | 24 |
| 9sp+ | 7 | 441sp+ | 25 |
| 16sp+ | 8 | 484sp+ | 26 |
| 25sp+ | 9 | 529sp+ | 27 |
| 36sp+ | 10 | 576sp+ | 28 |
| 49sp+ | 11 | 625sp+ | 29 |
| 64sp+ | 12 | 676sp+ | 30 |
| 81sp+ | 13 | 729sp+ | 31 |
| 100sp+ | 14 | 784sp+ | 32 |
| 121sp+ | 15 | 841sp+ | 33 |
| 144sp+ | 16 | 900sp+ | 34 |
| 169sp+ | 17 | 961sp+ | 35 |
| 196sp+ | 18 | 1024sp+ | 36 |
| 225sp+ | 19 | 1089sp+ | 37 |
| 256sp+ | 20 | 1156sp+ | 38 |
| 289sp+ | 21 | 1225sp+ | 39 |
| 324sp+ | 22 | 1296sp+ | 40 |
 
Your craft roll determines both the amount of progress made and the immediate cost of that progress. Any costs paid represent the raw ingredients that are used to craft the item. Make sure to prepare enough money to pay for the item. If you can't pay for your progress, then no progress is made. The cost you pay is equal to the cost of the item, multiplied by the amount of progress made, multiplied by a modifier value:

***Double Critical:*** Gain 100% progress paying 50% of the cost.  
***Critical:*** Gain 50% progress paying 50% of the cost.  
***Success:*** Gain 20% progress paying 75% of the cost.  
***Graze:*** Gain 10% progress paying 90% of the cost.  
***Fail:*** Gain 2% progress paying 100% of the cost.  
***Fumble:*** Lose 5% progress.

If you roll three times the difficulty or higher, that is considered a double critical.

Each craft check made represents a single day's worth of crafting time spent on that item.

> ##### Crafting Example
> ___
> **Craft:** r12
>
> **Intelligence:** r12+1
>
> **Craft Check Roll:** r24+1
> ___
> **Item:** Brigandine
>
> **Cost:** 40sp
>
> **Difficulty:** 10
>
> | Roll | Progress | Cost |
> |:-:|:-:|:-:|
> | 12 (Success) | +20% = 20% | 6sp (75%) |
> | 16 (Success) | +20% = 40% | 6sp (75%) |
> | 10 (Graze) | +10% = 50% | 3sp 6cp (90%) |
> | 6 (Fail) | +2% = 52% | 8cp (100%) |
> | 13 (Success) | +20% = 72% | 6sp (75%) |
> | 21 (Critical) | +50% (28%) = 100% | 5sp 6cp (50%) |
> ___
> **Time Spent:** 6 Days
>
> **Total Cost:** 28sp (70% of cost)

### Upgrading Items

Crafting can also be used to upgrade items from one quality to the next by treating the difference in item value as the cost of the item. You cannot upgrade into a quality with a cost reduction.

> ##### Upgrade Example
> ___
> **Item:** Longsword -> Fine Longsword
>
> **Cost:** 10sp (10sp to 20sp)
>
> **Difficulty:** 7
>
> | Roll | Progress | Cost |
> |:-:|:-:|:-:|
> | 7 (Graze) | +10% = 10% | 9cp (90%) |
> | 17 (Critical) | +50% = 60% | 2sp 5cp (50%) |
> | 11 (Success) | +20% = 80% | 1sp 5cp (75%) |
> | 19 (Critical) | +50% (20%) = 100% | 1sp (50%) |
> ___
> **Time Spent:** 4 Days
>
> **Total Cost:** 5sp 9cp (59% of cost)

Items in progress cannot be used until they are completed.

### Bulk Crafting

Some items are cheap and easy enough to make that you may want to produce them in large quantities. Treat the combined value of those items as if they were a single item for determining total cost and crafting difficulty. Items can only be crafted in bulk if all items being produced are exactly the same.

If partial progress is enough to represent one or more complete items, treat those items as completed. This also means that fumbles can only cause you to lose progress only on the quantity of items still in progress.

> ##### Bulk Crafting Example
> ___
> **Item:** 5 Javelins
>
> **Cost:** 10sp (2sp × 5)
>
> **Difficulty:** 7
>
> | Roll | Progress | Cost |
> |:-:|:-:|:-:|
> | 13 (Success) | +20% = 20% | 1sp 5cp (75%) |
> | 16 (Critical) | +50% = 70% | 2sp 5cp (50%) |
> ___
> **Time Spent:** 2 Days
>
> **Total Cost:** 4sp (40% of cost)

In this example, 70% of five javelins was crafted over two days. This translates to three complete javelins (which can be used immediately), half of one, and prepared work for another.

This progress can be resumed at a later date, leading us to the next example:

> ##### Bulk Crafting Example (Precrafted)
> ___
> **Item:** 5 Javelins
>
> **Precrafted:** 70%
>
> **Cost:** 10sp (2sp × 5)
>
> **Difficulty:** 7
>
> | Roll | Progress | Cost |
> |:-:|:-:|:-:|
> | - | 70% | - |
> | 7 (Graze) | +10% = 80% | 9cp (90%) |
> | 3 (Fumble) | –5% (0%) = 80% | - |
> | 12 (Success) | +20% = 100% | 1sp 5cp (75%) |
> ___
> **Time Spent:** 3 Days
>
> **Total Cost:** 2sp 4cp (24% of remaining cost)

You might notice that on the second of these last three days, that no progress was actually lost. This is because upon reaching 80% of the total progress the day before, a whole javelin was crafted. Since there was no partially crafted javelin remaining, progress could not be lost on any partially created items.

The maximum number of items that can be crafted at once is twenty, regardless of the percentage of crafting gained.

### Long-term Crafting

If you expect a craft project to take a large amount of time (upwards of 50 in-game days), rather than rolling 50 times, you may process the crafting in 6-day chunks. You do this by making a single crafting roll, then approximate the next 5 days with your average roll. To determine your average roll, take half your maximum craft roll, add any bonuses, then add 1 for every two dice you would roll. This shortcut is only available if it is expected that the item (as a whole) will take much longer than 5 days to craft. This can be done by checking if your average roll is less than the crafting difficulty.

> ##### Long-term Crafting Example
> ___
> **Craft:** r12
>
> **Intelligence:** r12+1
>
> **Craft Check Roll:** r24+1
>
> **Average Craft Roll:** 14
> ___
> **Item:** Superior Light Cuirass
>
> **Cost:** 150sp
>
> **Difficulty:** 16
>
> | Roll | Progress | Cost |
> |:-:|:-:|:-:|
> | 18 (Success) | +20% = 20% | 22sp 5cp (75%) |
> | 14 (Fail, Auto ×5) | +2% ×5 (10%) = 30% | 3sp (100%) ×5 (15sp) |
> | 11 (Fail) | +2% = 32% | 3sp (100%) |
> | 14 (Fail, Auto ×5) | +2% ×5 (10%) = 42% | 3sp (100%) ×5 (15sp) |
> | 16 (Graze) | +10% = 52% | 13sp 5cp (90%) |
> | 14 (Fail, Auto ×5) | +2% ×5 (10%) = 62% | 3sp (100%) ×5 (15sp) |
> | 8 (Fumble) | –5% = 57% | - |
> | 14 (Fail, Auto ×5) | +2% ×5 (10%) = 67% | 3sp (100%) ×5 (15sp) |
> | 17 (Success) | +20% = 87% | 22sp 5cp (75%) |
> | 14 (Fail, Auto ×5) | +2% ×5 (10%) = 97% | 3sp (100%) ×5 (15sp) |
> | 13 (Fail) | +2% = 99% | 3sp (100%) |
> | 14 (Fail, Auto ×1) | +2% (1%) = 100% | 1sp 5cp (100%) |
> ___
> **Time Spent:** 32 Days
>
> **Total Cost:** 141sp (94% of cost)

### Rushed Crafting

If speed is more important than cost you can "rush" your craft check. You can make rushed craft checks while long-term crafting. Rushed crafting alters the precentage of progress made and how much it costs at each success category:

***Double Critical:*** Gain 100% progress paying 75% of the cost.  
***Critical:*** Gain 75% progress paying 75% of the cost.  
***Success:*** Gain 50% progress paying 90% of the cost.  
***Graze:*** Gain 20% progress paying 100% of the cost.  
***Fail:*** Gain 5% progress paying 125% of the cost.  
***Fumble:*** Lose 10% progress.

> ##### Rushed Crafting Example
> ___
> **Item:** Brigandine
>
> **Cost:** 40sp
>
> **Difficulty:** 10
>
> | Roll | Progress | Cost |
> |:-:|:-:|:-:|
> | 12 (Success) | +50% = 50% | 18sp (90%) |
> | 16 (Success) | +50% = 100% | 18sp (90%) |
> ___
> **Time Spent:** 2 Days
>
> **Total Cost:** 36sp (90% of cost)

> ##### Rushed Long-term Crafting Example
> ___
> **Craft:** r12
>
> **Intelligence:** r12+1
>
> **Craft Check Roll:** r24+1
>
> **Average Craft Roll:** 14
> ___
> **Item:** Superior Light Cuirass
>
> **Cost:** 150sp
>
> **Difficulty:** 16
>
> | Roll | Progress | Cost |
> |:-:|:-:|:-:|
> | 18 (Success) | +50% = 50% | 67sp 5cp (90%) |
> | 14 (Fail, Auto x5) | +5% ×5 (25%) = 75% | 9sp 4cp (125%) ×5 (47sp) |
> | 11 (Fail) | +5% = 80% | 9sp 4cp (125%) |
> | 14 (Fail, Auto x4) | +5% ×4 (20%) = 100% | 9sp 4cp ×4 (125%) (37sp 6cp) |
> ___
> **Time Spent:** 11 Days
>
> **Total Cost:** 161sp 5cp (107.7% of cost)

## Magic Item Crafting

The cost for determining a magic item craft is found by combining two values together: the *base item cost*(which is the cost of the item including any adjustments from [equipment properties](/Fantasy/Equipment.md#equipment-properties)), and *magic effect cost*.

As an equation: the total cost = the base item cost + the magic effect cost

There are a few decisions that are requried to determine the cost of magic effects: the *spell required* to create the effect, the *application of the spell*, and *how many magical effects* are present on the item. The spell required determines the *base magic cost*, while the other decisions act as multipliers on this value.

In addition to this there are also bonus magic effects, which include: [triggered effects](#triggered-effects), [curses](#curses), [magic stabilization](#magic-stabilization), [charge bonding](#charge-bonding), and [mana focusing](#mana-focusing). These bonus effects don't have a base magic cost, but do count as additional effects for the purposes of acting as a cost multiplier. An item cannot have a bonus magic effect if they do not also have a normal magic effect.

Below is a table to use as a shortcut for determining costs and multipliers:

##### Table: Magical Item Costs
| Modifier | Cost Formula |
|:-|:-|
| Base Magic Cost | Mana Cost × Spell Difficulty |
| Limited Uses | Base Magic Cost × Uses ÷ 5 |
| Uses per Day | Base Magic Cost × Uses × 2 |
| Continuous Use | Base Magic Cost × 5 |
| Multiple<br/>Effects | Combined Magic Costs<br/>× (1 + Number of Additional Effects × ½) |

### Base Magic Cost

At its simplest, the base magic cost is equal to the mana cost of the spell multiplied by the difficulty to cast that spell. This provides access to the spell at its minimum possible effectiveness (a graze).

For example: if you choose the spell *mend*, this would by 2 multiplied by 10, for a total of 20.

The effectiveness of a magic effect is determined by the spell difficulty, which can be changed to any value. At a minimum this value must be at least equal to the spell's required difficulty, and at a maximum no higher than the maximum possible roll to cast that spell (after bonuses and penalties) that you or an assistant can cast.

For example: if you choose the spell *mend*, you could choose a difficulty of 20. This would effectively double the previous example's total to 40.

In part of determining the magic effect, you must also make any decisions that the spell must normally make. This includes decisions that alter the cost and difficulty to cast the spell, any modal or elemental decisions that the spell requires, and even metamagics. Any other modifers from talents or any unique features of spellcasting skills cannot be used to alter spells crafted onto items.

Crafting items using metamagics has a few restrictions. Adjustments made by metamagics cannot reduce the mana cost below its base mana cost, and it cannot reduce the spellcasting difficulty to zero. This restrction does not prevent those metamagics from being applied, it only prevents them from reducing these values in this way. Similar to the normal application of metamagics, crafted items cannot have metamagics applied that would generate no change in their use.

For example: continuous use items cannot be made with either the channelled or fickle metamagics because using them does not count as casting a spell and their effects do not have a set duration.

### Scrolls

This is the simplest form of magic item craft. Scrolls are made by inscribing the details of how to cast a spell into a some form of paper (generally of negligible value) or a page in a book. A scroll can only contain enough information for one spell. While technically the scroll itself is not magical, it does use the same crafting rules. Only spells provided by the arcana skill can be made into scrolls.

Only the bare minimum base magic cost of a single spell is required for determining the cost of scrolls. No other multipliers are applied.

For example: if you wanted to make a scroll of the spell *arcane missiles*, it would simply be 2 multiplied by 20, for a total of 20.

### Limited Use Items

These types of items can take two forms: *potions* and *spellstones*. Both use the same cost multiplier. This multipler is equal to a ratio of how many uses it holds divided by 5.

Potions can only be made as single use items, while spellstones can be made with any quantity of uses. The base item cost is 1 silver (or an alchemical base) to create potions. Spellstones come in several different qualities: 2 silver for a rough gemstone, 10 silver for a fine gemstone, or 100 silver for a magnificent gemstone.

Potions are limited to certain types of spells. Only spells that can target a creature or a point, regardless of their other targeting options, can be made into potions. The spellcasting difficulty chosen pre-determines the spellcasting roll made when applying the effects of potions. 

> ##### Potion Crafting Example
> ___
> **Item:** Potion of Mending
>
> **Spell:** Mend
>
> **Mana Cost:** 2
>
> **Spell Difficulty:** 11 (+1 for success effect)
>
> **Effect Cost:** 4.4 = 2 × 11 × 1 ÷ 5 (1 limited use)
>
> **Cost:** 5sp 4cp (1sp for the alchemical base, 4sp 4cp for the effect)
>
> **Difficulty:** 6

Any spell can be chosen when crafting spellstones. For spellstones, the spellcasting difficulty determines the automatic minimum that they are cast with. This value is equal to half of the spellcasting difficulty chosen for the craft.

> ##### Spellstone Crafting Example
> ___
> **Item:** Spellstone of Ignition (5 uses)
>
> **Spell:** Ignite
>
> **Mana Cost:** 1
>
> **Spell Difficulty:** 8 (automatic minimum of 4)
>
> **Effect Cost:** 8 = 1 × 8 × 5 ÷ 5 (5 limited uses)
>
> **Cost:** 10sp (2sp for the gemstone, 8sp for the effect)
>
> **Difficulty:** 7

Spellstones can also be socketed into another item (such as a ring), allowing that item to cast spells from the spellstone. No crafting check is necessary to socket spellstones into other items, however, they will be unusable if the item is already magical or has other spellstones socketed. This restriction can be circumvented with the bonus magic effect of [magic stabilization](#magic-stabilization), or by crafting multiple effects onto one spellstone (avoiding the problem entirely).

### Multiple Use Items

These types of items are very similar to limited use items. They even take the same two forms: *potions* and *spellstones*. The primary difference is that rather than having a total limited number of uses, these types of items can be used a limited number of times *per day*. The cost multiplier for this type of item is equal to the number of times per day it can be used multiplied by 2.

Multiple use potions are called refilling potions and can only be used once per day. Spellstones can still be crafted with any number of uses.

### Continuous Use Items

Continuous effects are placed on items that are used or worn. Spells used to make these types of items effect either their wearer or the item itself. Only spells that require concentration can be chosen. These types of items must be attuned to activate their effect. The cost multipler for this type of item is 5.

Typically this effect is placed on articles of clothing, like boots, gloves, cloaks, belts, etc. It is likely that this type of craft is performed on existing items, rather than from scratch, but both options are allowed.

> ##### Continuous Use Item Upgrade Example
> ___
> **Item:** Fine Longsword -> Flaming Fine Longsword
>
> **Spell:** Magic Weapon (fire)
>
> **Mana Cost:** 2
>
> **Spell Difficulty:** 10
>
> **Effect Cost:** 100 = 2 × 10 × 5 (continuous)
>
> **Cost:** 100sp (100sp for the effect, on a 20sp item)
>
> **Difficulty:** 14

### Multiple Effects

Magic items are not limited to a single magic effect, but there is an additional multipler for items that have more than one. You start by combining the costs of each individual effect, then you apply a multiplier to this combined cost. This multiplier is equal to one plus one half for each magical effect beyond the first.

As an equation: the total cost = the base item cost + the combined cost of all magical effects × (1 + the number of additional effects × ½)

Bonus magic effects ([triggered effects](#triggered-effects), [curses](#curses), [magic stabilization](#magic-stabilization), [charge bonding](#charge-bonding), and [mana focusing](#mana-focusing)) don't have a base magic cost, but do count as additional effects. As additional effects they will contribute a multiplier which increases the cost of the item. An item cannot have a bonus magic effect if they do not have a normal magic effect.

Attuning to a single item with multiple continuous effects allows you to use any combination of those effects, even simultaneously.

> ##### Multiple Effects Crafting Example
> ___
> **Item:** Spellstone of Ignition (5 Uses) and Electricity (5 Uses)
>
> **Spell:** Ignite, Jolt
>
> **Mana Cost:** 1 (both spells)
>
> **Spell Difficulty:** 8 (automatic minimum of 4) (both spells)
>
> **Effect Cost:** 8 = 1 × 8 × 5 ÷ 5 (5 limited uses) (both spells)
>
> **Combined Cost, with Multiplier:** 24 = (8 + 8) × (1 + 1 × ½) = 16 × 1½ (one additional effect)
>
> **Cost (Difference):** 26sp (2sp for the gemstone, 24sp for the effect)
>
> **Difficulty:** 9

### Triggered Effects

Any type of spell effect application can become triggered: *limited*, *per day*, and even *continuous*. The trigger sets a condition for it to be activated, and it must be activated in this way to be used.

Most metamagics provide small adjustments to spells in terms of mana cost and spell difficulty. Spells modified by the *triggered* metamagic are a bit special. Rather than applying the cost of the triggered metamagic to the mana cost and spell difficulty, treat the trigger as a bonus magic effect. This means it has no base mana cost, but still increases the multiplier for having multiple effects.

Triggers that apply under conditions outside of the user's control simply happen and do not require the use of actions. Any triggers that require user activation are considered swift actions. Once an item is triggered, if it requires attunement, the item's user is alerted (if it happened outside of their control) and they must decide in that moment if they want to attune to it. They may choose to manually attune to it so long as the condition for that trigger is met.

Triggers on items follow the same rules as usual for triggered metamagics with one bonus rule: any condition is valid so long as it is knowable by the user, provided by the context of the spell, or involves detection of details within 100m from the user's location (even if not otherwise known).

> ##### Triggered Item Upgrade Example
> ___
> **Item:** Straight Sword -> Straight Sword of Orc Detection
>
> **Spell:** Light (blue light, reduced metamagic)
>
> **Condition:** Orcs are nearby (100m)
>
> **Mana Cost:** 1
>
> **Spell Difficulty:** 6 (–1 from reduced)
>
> **Effect Cost:** 45 = 1 × 6 × 5 × 1.5 (continuous, triggered)
>
> **Cost:** 45sp (45sp for the effect, on a 5sp item)
>
> **Difficulty:** 10

### Curses

Curses are a special type of triggered effect. They are applied to items in the same way as normal triggered effects. The condition specified by a curse does not trigger a spell, instead it provides context for a drawback. There are two types of curses: *limitation* curses and *shackling* curses. An item can have both kinds of curses, but only one of each.

Limitation curses provide restrictions how on the item is allowed to be used. These limitations can either prevent the item from providing magical effects or by directly influencing the actions of their users.

Shackling curses are much more prohibitive than limitation curses. Once attuned to an item with a shackling curse, the item cannot be removed or deattuned except by a spell that removes or disables the curse, or by meeting the conditions of the curse.

All cursed items have conditions, even if they are not always known to their user.

Curses follow similar conditions to triggered effects: any condition is valid so long as it is knowable by the user, provided by the context of the curse, or involves detection of details within 100m from the user's location (even if not otherwise known).

### Magic Stabilization

Spellstones socketed into items conflict with other spellstones and other magic effects on those items. This renders all of these items unusable until the conflict is resolved. In order to circumvent this problem and allow compatibility, both spellstones and other items can be magic stabilized. Items with this effect are only compatible with other items that also have this effect.

Magic stabilization is a bonus effect, so it has no base magic cost. This means it has no base mana cost, but still increases the multiplier for having multiple effects.

> ##### Magic Stabilization Upgrade Example
> ___
> **Item:** Spellstone of Ignition (5 Uses) -> Stabilized
>
> **Spell:** Ignite
>
> **Mana Cost:** 1
>
> **Spell Difficulty:** 8 (+1 for success effect)
>
> **Effect Cost:** 8 = 1 × 8 × 5 ÷ 5 (5 limited uses)
>
> **Combined Cost, with Multiplier:** 12 = 8 × (1 + 1 × ½) = 8 × 1½ (one additional effect) 
>
> **Cost (Difference):** 4sp (4sp for the effect, on a 10sp item)
>
> **Difficulty:** 6

### Charge Bonding

Like magic stabilization this is a bonus effect. Meaning it has no base mana cost, but still increases the multiplier for having multiple effects.

The purpose of charge bonding is to unify the collective usage effects on spellstones. For example, if a spellstone can cast the spells inspire and suggestion each once a day. After that spellstone is charge bonded, it can cast either of them, collectively, twice a day. So one day it could be used to cast inspire twice, then the next day suggestion twice.

This effect only to all spells in that spellstone, but only those collectively that are of the same category of spell usage (limited use or per day), even if those spells have a different mana cost or spell difficulty.

For example: A spellstone with limited uses of jolt but per day uses of inspire and suggestion, could interchangably use inspire and suggestion. It could not use its per day uses to cast jolt, and vice versa.

### Mana Focusing

Mana focusing is another bonus effect. Meaning it has no base mana cost, but still increases the multiplier for having multiple effects.

This effect, like charge bonding, increases the versatility of spellstones. Spellstones with this effect are no longer limited by their per day uses, but in order to cast spells exceeding their per day limit, those spells will cost mana instead. Casting spells in this way is only possible to characters who have a skill appropriate to cast those spells, even if they do not have that spell learned.

Limited use magic effects gain no bonus from mana focusing.