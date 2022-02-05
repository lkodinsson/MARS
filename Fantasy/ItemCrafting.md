# Item Crafting

* [Normal Item Crafting](#normal-item-crafting)
* [Upgrading Items](#upgrading-items)
* [Bulk Crafting](#bulk-crafting)
* [Long-term Crafting](#long-term-crafting)
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

## Normal Item Crafting

The first step to crafting an item is just a matter of roleplaying: is a workshop or marketplace available, or do you carry the tools and materials necessary to build this item? Afterwards, there are three basic steps:

* Determine the total cost and craft difficulty
* Roll a craft check
* Determine craft progress and pay the immediate cost

The difficulty value to craft an item is based on its cost. This can be determined manually by finding the square root of the cost in silver pieces, then adding 4 to the result. The following table can be used as a quick reference:

##### Table: Item Cost vs Craft Difficulty
| Item Cost | Difficulty | Item Cost | Difficulty |
|:-:|:-:|:-:|:-:|
| 1sp+ | 5 | 225sp+ | 19 |
| 4sp+ | 6 | 256sp+ | 20 |
| 9sp+ | 7 | 289sp+ | 21 |
| 16sp+ | 8 | 324sp+ | 22 |
| 25sp+ | 9 | 361sp+ | 23 |
| 36sp+ | 10 | 400sp+ | 24 |
| 49sp+ | 11 | 441sp+ | 25 |
| 64sp+ | 12 | 484sp+ | 26 |
| 81sp+ | 13 | 529sp+ | 27 |
| 100sp+ | 14 | 576sp+ | 28 |
| 121sp+ | 15 | 625sp+ | 29 |
| 144sp+ | 16 | 676sp+ | 30 |
| 169sp+ | 17 | 729sp+ | 31 |
| 196sp+ | 18 | 784sp+ | 32 |

Your craft roll determines both the amount of progress made and the immediate cost of that progress. Any costs paid represent the raw ingredients that are used to craft the item. Make sure to prepare enough money to pay for the item. If you can't pay for your progress, then no progress is made. The cost you pay is equal to the cost of the item, multiplied by the amount of progress made, multiplied by a modifier value:

***Double Critical:*** Gain 100% progress paying 50% of the cost.  
***Critical:*** Gain 50% progress paying 50% of the cost.  
***Success:*** Gain 20% progress paying 75% of the cost.  
***Graze:*** Gain 10% progress paying 100% of the cost.  
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
> | 12 (Success) | +20% = 20% | 6sp |
> | 16 (Success) | +20% = 40% | 6sp |
> | 10 (Graze) | +10% = 50% | 4sp |
> | 6 (Fail) | +2% = 52% | 8cp |
> | 13 (Success) | +20% = 72% | 6sp |
> | 21 (Critical) | +50% (28%) = 100% | 5sp 6cp |
> ___
> **Time Spent:** 6 Days
>
> **Total Cost:** 28sp 4cp (71% of cost)

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
> | 7 (Graze) | +10% = 10% | 1sp |
> | 17 (Critical) | +50% = 60% | 2sp 3cp |
> | 11 (Success) | +20% = 80% | 2sp |
> | 19 (Critical) | +50% (20%) = 100% | 1sp |
> ___
> **Time Spent:** 4 Days
>
> **Total Cost:** 6sp 3cp (63% of cost)

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
> | 13 (Success) | +20% = 20% | 1sp 5cp |
> | 16 (Critical) | +50% = 70% | 2sp 5cp |
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
> | 7 (Graze) | +10% = 80% | 1sp |
> | 3 (Fumble) | –5% (0%) = 80% | - |
> | 12 (Success) | +20% = 100% | 1sp 5cp |
> ___
> **Time Spent:** 3 Days
>
> **Total Cost:** 2sp 5cp (25% of remaining cost)

You might notice that on the second of these last three days, that no progress was actually lost. This is because upon reaching 80% of the total progress the day before, a whole javelin was crafted. Since there was no partially crafted javelin remaining, progress could not be lost on any partially created items.

The maximum number of items that can be crafted at once is twenty, regardless of the percentage of crafting gained.

### Long-term Crafting

If you expect a craft project to take a large amount of time (upwards of 50 in-game days), rather than rolling 50 times, you may process the crafting in 6-day chunks. You do this by making a single crafting roll, then approximate the next 5 days with your average roll. To determine your average roll, take half your maximum craft roll, add any bonuses, then add 1 for every two dice you would roll. This shortcut is only available if it is expected that the item (as a whole) will take much longer than 5 days to craft. This can be done by checking if your average roll is less than the crafting difficulty.

> ##### Long-term Example
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
> | 18 (Success) | +20% = 20% | 22sp 5cp |
> | 14 (Fail, Auto x5) | +10% = 30% | 15sp |
> | 11 (Fail) | +2% = 32% | 3sp |
> | 14 (Fail, Auto x5) | +10% = 42% | 15sp |
> | 16 (Graze) | +10% = 52% | 15sp |
> | 14 (Fail, Auto x5) | +10% = 62% | 15sp |
> | 8 (Fumble) | –5% = 57% | - |
> | 14 (Fail, Auto x5) | +10% = 67% | 15sp |
> | 17 (Success) | +20% = 87% | 22sp 5cp |
> | 14 (Fail, Auto x5) | +10% = 97% | 15sp |
> | 13 (Fail) | +2% = 99% | 3sp |
> | 14 (Fail, Auto x1) | +2% (1%) = 100% | 1sp 5cp |
> ___
> **Time Spent:** 32 Days
>
> **Total Cost:** 142sp 5cp (95% of cost)

## Magic Item Crafting

Similar to normal items, magic items can be crafted in two ways: you can craft the whole item, or you can craft the base item then craft magic effects onto it after. This cost for this is determined by combining two values together: the *base item cost* (which is the cost of the item including any adjustments from [equipment properties](/Fantasy/Equipment.md#equipment-properties)) plus the *combined cost of all magic effects*.

In short: the total cost = base item cost + combined cost of all magic effects

There are a few decisions that are requried to determine the cost of magic effects. If its a standard magic effect: the *spell required* to create the effect, the *application of the spell*, and *how many magical effects* are present on the item. The spell required determines the base magic cost, while the other decisions act as multipliers on this value.

In addition to a standard magic effect, there is also a bonus magic effect. Bonus magic effects include: [triggered effects](#triggered-effects), [curses](#curses), [magic stabilization](#magic-stabilization), [charge bonding](#charge-bonding), and [mana focusing](#mana-focusing). These bonus effects don't have a base magic cost, but do count as additional effects. As additional effects they will contribute a multiplier which increases the cost of the item. An item cannot have a bonus magic effect if they do not have a base magic effect.

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

In essence, the spell difficulty value is used to predetermine the effectiveness of that spell as if it was pre-rolled. This also means you can change this value to any other value to increase the effectiveness of the magical effect. If you wanted a spell to have the effectiveness of a critical, you would set the difficulty value to twice the spell's spellcasting difficulty.

For example: if you choose the spell *mend*, and you want it to have a critical effect, it would be a mana cost of 2 multiplied by a difficulty value of 20 (twice the spell's required difficulty value).

At a minimum this value must be at least equal to the spell's required difficulty, and at a maximum no higher than the maximum possible roll to cast that spell (after bonuses and penalties) that you or an assistant can cast.

In part of determining this cost, you must also make any decisions that spell must normally make. This includes decisions that alter the cost and difficulty to cast the spell, any modal or elemental decisions that the spell requires, and even metamagics. Adjustments made by metamagics cannot reduce either the mana cost or the spellcasting difficulty to zero. This restrction does not prevent those metamagics from being applied, it only prevents them from reducing these values to zero. Any other modifers from talents or any unique features of spellcasting skills cannot be used to alter spells crafted onto items.

The only time you are required to specify a target, is when the spell chosen requires concentration. If that is the case, you will either pick self or other as a targeting restriction, and that spell now requires that the item be attuned to rather than having concentration maintained.

### Scrolls

This is the simplest form of magic item craft. It is made by inscribing the details of how to cast a spell into a some form of paper (generally of negligible value) or a page in a book. A scroll can only contain enough information for one spell. While technically the scroll itself is not magical, it does use the same crafting rules. Only spells provided by the arcana skill can be made into scrolls.

Only the bare minimum base magic cost of a single spell is required for determining the cost of scrolls. No other multipliers are applied.

### Limited Use Items

These types of items can take two forms: *potions* and *spellstones*. Both use the same cost multiplier. This multipler is equal to a ratio of how many uses it holds divided by 5.

Potions can only be made as single use items, while spellstones can be made with any quantity of uses. The base item cost is 1 silver (or an alchemical base) to create potions, and 2 silver (or a rough gemstone) to create spellstones.

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

> ##### Spellstone Crafting Example
> ___
> **Item:** Spellstone of Ignition (5 uses)
>
> **Spell:** Ignite
>
> **Mana Cost:** 1
>
> **Spell Difficulty:** 8 (+1 for success effect)
>
> **Effect Cost:** 8 = 1 × 8 × 5 ÷ 5 (5 limited uses)
>
> **Cost:** 10sp (2sp for the gemstone, 8sp for the effect)
>
> **Difficulty:** 7

Spellstones can also be socketed into another item (such as a ring), allowing that item to cast spells from the spellstone. No crafting check is necessary to socket spellstones into other items, however, they will be unusable if the item is already magical or has other spellstones socketed. This restriction can be circumvented with the bonus magic effect of [magic stabilization](#magic-stabilization), or by crafting multiple effects onto one spellstone (avoiding the problem entirely).

### Multiple Use Items

These types of items are very similar to limited use items. They even take the same two forms: *potions* and *spellstones*. The primary difference is that rather than having a total limited number of uses, these types of items can be used a limited number of times *per day*. The cost multiplier for this type of item is equal to twice the number of times per day it can be used.

Multiple use potions are called refilling potions and can only be used once per day. Spellstones can still be crafted with any number of uses and are called fine spellstones when reusable. The base item cost is still 1 silver (or an alchemical base) to create refilling potions, but 10 silver (or a fine gemstone) to create fine spellstones.

### Continuous Use Items

Continuous effects are placed on items that are used or worn. Spells used to make these types of items effect either their wearer or the item itself. Only spells that require concentration can be chosen. These types of items must be attuned to activate their effect. The cost multipler for this type of item is 5.

Typically this effect is placed on articles of clothing, like boots, gloves, cloaks, belts, etc. The base item cost is 1 silver to create items of this kind on articles of clothing. It is likely that this type of craft is performed on existing items, rather than from scratch, but both options are allowed.

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

In short: the total cost = base item cost + combined cost of all magical effects × (1 + the number of additional effects × ½)

Bonus magic effects, like [triggered effects](#triggered-effects), [curses](#curses), [magic stabilization](#magic-stabilization), [charge bonding](#charge-bonding), and [mana focusing](#mana-focusing), also contribute to the total number of effects. These bonus effects don't have a base magic cost, but do count as additional effects. As additional effects they will contribute a multiplier which increases the cost of the item. An item cannot have a bonus magic effect if they do not have a base magic effect.

Attuning to a single item with multiple continuous effects allows you to use any combination of those effects, even simultaneously.

> ##### Multiple Effects Crafting Example
> ___
> **Item:** Spellstone of Ignition (5 Uses) and Jolt (5 Uses)
>
> **Spell:** Ignite, Jolt
>
> **Mana Cost:** 1 (both spells)
>
> **Spell Difficulty:** 8 (+1 for success effect) (both spells)
>
> **Effect Cost:** 8 = 1 × 8 × 5 ÷ 5 (5 limited uses) (both spells)
>
> **Combined Cost, with Multiplier:** 24 = (8 + 8) × (1 + 1 × ½) = 16 × 1½ (one additional effect)
>
> **Cost (Difference):** 26sp (2sp for the gemstone, 24sp for the effect)
>
> **Difficulty:** 9

### Triggered Effects

Any type of spell effect application can become triggered: *limited*, *per day*, and even *continuous*. The trigger sets a condition for it to be activated, and it must be activated in this way.

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

Curses are a special type of triggered effect. They are applied to items in the same way, including the increased cost, but with some minor differences. The condition specified by a curse does not trigger a spell. Instead, if a player attunes to a cursed magic item, then it cannot be removed except by a spell that removes the curse or the conditions of the curse being met. Cursed items may be provided with details on how to meet their conditions, others may not. All cursed items have conditions, even if they are not always known to their user.

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