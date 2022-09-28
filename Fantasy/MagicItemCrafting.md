# Table of Contents

* [Magic Item Crafting](#magic-item-crafting)
* [Base Magic Cost](#base-magic-cost)
* [Scrolls](#scrolls)
* [Limited Use Items](#limited-use-items)
* [Multiple Use Items](#multiple-use-items)
* [Continuous Use Items](#continuous-use-items)
* [Multiple Effects](#multiple-effects)
* [Triggered Effects](#triggered-effects)
* [Curses](#curses)
* [Charge Bonding](#charge-bonding)
* [Focusing](#focusing)

Click [here](/Fantasy/MagicEquipment.md) for examples of low cost magic equipment, or [here](/Fantasy/ArtifactEquipment.md) for examples of high cost magic equipment.

## Magic Item Crafting

The cost for determining a magic item craft is found by combining two values together: the *base item cost* (which is the cost of the item including any adjustments from [equipment properties](/Fantasy/Equipment.md#equipment-properties)), and *magic effect cost*.

As an equation: the total cost = the base item cost + the magic effect cost

There are a few decisions that are requried to determine the cost of magic effects: the *spell required* to create the effect, the *application of the spell*, and *how many magical effects* are present on the item. The spell required determines the *base magic cost*, while the other decisions act as multipliers on this value.

In addition to this there are also bonus magic effects, which include: [triggered effects](#triggered-effects), [curses](#curses), [charge bonding](#charge-bonding), and [focusing](#focusing). These bonus effects don't have a base magic cost, but do count as additional effects for the purposes of acting as a cost multiplier. An item cannot have a bonus magic effect if they do not also have a normal magic effect.

Below is a table to use as a shortcut for determining costs and multipliers:

##### Table: Magical Item Costs
| Modifier | Cost Formula |
|:-|:-|
| Base Magic Cost | Focus Cost × Spell Difficulty |
| Spell Scroll | Base Magic Cost × 1½ |
| Limited Uses | Base Magic Cost × Uses ÷ 5 |
| Uses per Day | Base Magic Cost × Uses × 2 |
| Continuous Use | Base Magic Cost × 5 |
| Multiple<br/>Effects | Combined Magic Costs<br/>× (½ + Number of Effects × ½) |

### Base Magic Cost

The base magic cost of an item is equal to the focus cost of the spell multiplied by the difficulty to cast that spell.

For example: if you choose the spell *mend*, this would be 2 multiplied by 10, for a total of 20.

The effectiveness of a magic effect is determined by the spell difficulty, which can be changed to any value. At a minimum this value must be at least equal to the spell's required difficulty, and at a maximum no higher than the maximum possible roll to cast that spell (after bonuses and penalties) that you or an assistant can cast.

For example: if you choose the spell *mend*, you could choose a difficulty of 20. This would effectively double the previous example's total to 40.

In part of determining the magic effect, you must also make any decisions that the spell must normally make. This includes decisions that alter the cost and difficulty to cast the spell, any modal or elemental decisions that the spell requires, and even metamagics. Any other modifers from talents or any unique features of spellcasting skills cannot be used to alter spells crafted onto items.

Crafting items using metamagics has a few restrictions. Adjustments made by metamagics cannot reduce the focus cost below its base focus cost, and it cannot reduce the spellcasting difficulty to zero. This restrction does not prevent those metamagics from being applied, it only prevents them from reducing these values in this way. Similar to the normal application of metamagics, crafted items cannot have metamagics applied that would generate no change in their use.

For example: continuous use items cannot be made with either the channelled or fickle metamagics because using them does not count as casting a spell and their effects do not have a set duration.

### Scrolls

This is the simplest form of magic item craft. Scrolls are made by inscribing the details of how to cast a spell into a some form of paper (generally of negligible value) or a page in a book. A scroll can only contain enough information for one spell. While technically the scroll itself is not magical, it does use the same crafting rules. Only spells provided by the arcana skill can be made into scrolls.

The cost to make a scroll is equal to the base magic cost multiplied by 1½.

For example: if you wanted to make a scroll of the spell *arcane missiles*, it would be 2 multiplied by 10, for a base magic cost of 20. Multiply that by 2, for a total cost of 40.

### Limited Use Items

These types of items can take two forms: *potions* and *spellstones*. Both use the same cost multiplier. This multipler is equal to a ratio of how many uses it holds divided by 5. Potions can only be made as single use items, while spellstones can be made with any quantity of uses.

Potions are limited to certain types of spells. Only spells that can target a creature or a point, regardless of their other targeting options, can be made into potions. The spellcasting difficulty chosen pre-determines the spellcasting roll made when applying the effects of potions. The base item cost is 1 silver (or an alchemical base) to create potions.

> ##### Potion Crafting Example
> ___
> **Item:** Potion of Mending
>
> **Spell:** Mend
>
> **Focus Cost:** 2
>
> **Spell Difficulty:** 10
>
> **Effect Cost:** 4 = 2 × 10 × 1 ÷ 5 (1 limited use)
>
> **Cost:** 5sp (1sp for the alchemical base, 4sp for the effect)
>
> **Difficulty:** 6

Any spell can be chosen when crafting spellstones, but you must be able to cast it. Spellstones come in several different qualities: 2 silver for a rough gemstone, 10 silver for a fine gemstone, 50 silver for an exceptional gemstone, and 100 silver for a magnificent gemstone.

> ##### Spellstone Crafting Example
> ___
> **Item:** Spellstone of Ignition (5 uses)
>
> **Spell:** Ignite
>
> **Focus Cost:** 1
>
> **Spell Difficulty:** 7
>
> **Effect Cost:** 7 = 1 × 3 × 5 ÷ 5 (5 limited uses)
>
> **Cost:** 9sp (2sp for the gemstone, 7sp for the effect)
>
> **Difficulty:** 7

Spellstones can also be socketed into another item (such as a ring), allowing that item to cast spells from the spellstone. No crafting check is necessary to socket spellstones into other items.

### Multiple Use Items

These types of items are very similar to limited use items. They even take the same two forms: *potions* and *spellstones*. The primary difference is that rather than having a total limited number of uses, these types of items can be used a limited number of times *per day*. The cost multiplier for this type of item is equal to the number of times per day it can be used multiplied by 2.

Multiple use potions are called refilling potions and can only be used once per day. Spellstones can still be crafted with any number of uses.

### Continuous Use Items

Continuous effects are placed on items that are used or worn. Spells used to make these types of items effect either their wearer or the item itself. Only spells that require concentration can be chosen. A character must attune to this type of item to activate their effect. The cost multipler for this type of item is 5.

Typically this effect is placed on articles of clothing, like boots, gloves, cloaks, belts, etc. It is likely that this type of craft is performed on existing items, rather than from scratch, but both options are allowed.

> ##### Continuous Use Item Upgrade Example
> ___
> **Item:** Fine Longsword -> Flaming Fine Longsword
>
> **Spell:** Magic Weapon (fire)
>
> **Focus Cost:** 2
>
> **Spell Difficulty:** 10
>
> **Effect Cost:** 100 = 2 × 10 × 5 (continuous)
>
> **Cost:** 100sp (100sp for the effect, on a 20sp item)
>
> **Difficulty:** 14

### Multiple Effects

Magic items are not limited to a single magic effect, but there is an additional multipler for items that have more than one effect. You start by combining the costs of each individual effect, then you apply a multiplier to this combined cost. This multiplier is equal to ½ plus ½ for each magical effect.

As an equation: the total cost = the base item cost + the combined cost of all magical effects × (½ + the number of effects × ½)

Bonus magic effects ([triggered effects](#triggered-effects), [curses](#curses), [charge bonding](#charge-bonding), and [focusing](#focusing)) don't have a base magic cost, but do count as additional effects. As additional effects they will contribute a multiplier which increases the cost of the item. An item cannot have a bonus magic effect if they do not have a normal magic effect.

Attuning to a single item with multiple continuous effects allows you to use any combination of those effects, even simultaneously.

> ##### Multiple Effects Crafting Example
> ___
> **Item:** Spellstone of Ignition (5 Uses) and Electricity (5 Uses)
>
> **Spell:** Ignite, Jolt
>
> **Focus Cost:** 1 (both spells)
>
> **Spell Difficulty:** 7 (both spells)
>
> **Effect Cost:** 7 = 1 × 7 × 5 ÷ 5 (5 limited uses) (both spells)
>
> **Combined Cost, with Multiplier:** 21 = (7 + 7) × (½ + 2 × ½) = 14 × 1½ (two effects)
>
> **Cost:** 23sp (2sp for the gemstone, 21sp for the effect)
>
> **Difficulty:** 8

### Triggered Effects

Any type of spell effect application can become triggered: *limited*, *per day*, and even *continuous*. The trigger sets a condition for it to be activated, and it must be activated in this way to be used.

Most metamagics provide small adjustments to spells in terms of focus cost and spell difficulty. Spells modified by the *triggered* metamagic are a bit special. Rather than applying the cost of the triggered metamagic to the focus cost and spell difficulty, treat the trigger as a bonus magic effect. This means it has no base focus cost, but still increases the multiplier for having multiple effects.

Triggers that apply under conditions outside of the user's control simply happen and do not require the use of actions. Any triggers that require user activation are considered swift actions. Once an item is triggered, if it requires attunement, the item's user is alerted (if it happened outside of their control) and they must decide in that moment if they want to attune to it. They may choose to manually attune to it so long as the condition for that trigger is met.

Triggers on items follow the same rules as usual for triggered metamagics with one bonus rule: any condition is valid so long as it is knowable by the user, provided by the context of the spell, or involves detection of details within 100m from the user's location (even if not otherwise known). A magic item can only perform one trigger at a time.

> ##### Triggered Item Upgrade Example
> ___
> **Item:** Straight Sword -> Straight Sword of Orc Detection
>
> **Spell:** Light (blue light, reduced metamagic)
>
> **Condition:** Orcs are nearby (100m)
>
> **Focus Cost:** 1
>
> **Spell Difficulty:** 6 (-1 from reduced)
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

### Charge Bonding

Charge bonding is a bonus effect. Meaning it has no base focus cost, but still increases the multiplier for having multiple effects.

The purpose of charge bonding is to unify the collective usage effects on spellstones. For example, if a spellstone can cast the spells *inspire* and *suggestion* each once a day. After that spellstone is charge bonded, it can cast either of them, collectively, twice a day. So one day it could be used to cast inspire twice, then the next day suggestion twice.

This effect applies to all spells in that spellstone that are of the same category of spell usage (limited use or per day), even if those spells have a different focus cost or spell difficulty.

For example: A spellstone with limited uses of jolt but per day uses of inspire and suggestion, could interchangably use inspire and suggestion. It could not use its per day uses to cast jolt, and vice versa.

### Focusing

Focusing is another bonus effect. Meaning it has no base focus cost, but still increases the multiplier for having multiple effects.

This effect, like charge bonding, increases the versatility of spellstones. Spellstones with this effect are no longer limited by their per day uses, but in order to cast spells exceeding their per day limit those spells will cost focus instead. Casting spells in this way is only possible to characters who have a skill appropriate to cast those spells, even if they do not have that spell learned.

Limited use magic effects gain no bonus from focusing.