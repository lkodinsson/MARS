# Table of Contents

* [Item Crafting](#item-crafting)
* [Upgrading Items](#upgrading-items)
* [Bulk Crafting](#bulk-crafting)
* [Long-term Crafting](#long-term-crafting)
* [Rushed Crafting](#rushed-crafting)

## Normal Item Crafting

The first step to crafting an item is just a matter of roleplaying: is a workshop or marketplace available, or do you carry the tools and materials necessary to build this item? Afterwards, there are three basic steps:

* Determine the total cost and craft difficulty
* Roll a craft check
* Determine craft progress and pay the immediate cost

The difficulty value to craft an item is based on its cost. This can be determined manually by finding the square root of the item's cost (rounded down), then adding 4 to the result. The following table can be used as a quick reference:

##### Table: Item Cost vs Craft Difficulty
| Item Cost | Difficulty | Item Cost | Difficulty |
|:-:|:-:|:-:|:-:|
| 1 | 5 | 361 | 23 |
| 4 | 6 | 400 | 24 |
| 9 | 7 | 441 | 25 |
| 16 | 8 | 484 | 26 |
| 25 | 9 | 529 | 27 |
| 36 | 10 | 576 | 28 |
| 49 | 11 | 625 | 29 |
| 64 | 12 | 676 | 30 |
| 81 | 13 | 729 | 31 |
| 100 | 14 | 784 | 32 |
| 121 | 15 | 841 | 33 |
| 144 | 16 | 900 | 34 |
| 169 | 17 | 961 | 35 |
| 196 | 18 | 1024 | 36 |
| 225 | 19 | 1089 | 37 |
| 256 | 20 | 1156 | 38 |
| 289 | 21 | 1225 | 39 |
| 324 | 22 | 1296 | 40 |
 
Your craft roll determines both the amount of progress made and the immediate cost of that progress. Any costs paid represent the raw ingredients that are used to craft the item. Make sure to prepare enough money to pay for the item. If you can't pay for your progress, then no progress is made. The cost you pay is equal to the cost of the item, multiplied by the amount of progress made, multiplied by a modifier value:

***Double Critical:*** Gain 100% progress paying 50% of the cost.  
***Critical:*** Gain 50% progress paying 50% of the cost.  
***Success:*** Gain 20% progress paying 75% of the cost.  
***Graze:*** Gain 2% progress paying 90% of the cost.  
***Fail:*** Lose 5% progress.

If you roll 14 above the difficulty or higher, that is considered a double critical.

Each craft check made represents a single day's worth of crafting time spent on that item. While an item is in progress, it cannot be used until it is completed.

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
> | 10 (Success) | +20% = 60% | 6sp (75%) |
> | 5 (Fail) | -5% = 55% | - |
> | 13 (Success) | +20% = 75% | 6sp (75%) |
> | 21 (Critical) | +25% (50%) = 100% | 5sp (50%) |
> ___
> **Time Spent:** 6 Days
>
> **Total Cost:** 29sp (72.5% of cost)

### Upgrading Items

Crafting can also be used to upgrade items from one quality to the next by treating the difference in item value as the cost of the item. You cannot upgrade into a quality with a cost reduction.

> ##### Upgrade Example
> ___
> **Item:** Longsword -> Fine Longsword
>
> **Cost:** 10sp (8sp to 18sp)
>
> **Difficulty:** 7
>
> | Roll | Progress | Cost |
> |:-:|:-:|:-:|
> | 6 (Graze) | +2% = 2% | 2cp (90%) |
> | 17 (Critical) | +50% = 52% | 2sp 5cp (50%) |
> | 11 (Success) | +20% = 72% | 1sp 5cp (75%) |
> | 19 (Critical) | +28% (50%) = 100% | 1sp 4cp (50%) |
> ___
> **Time Spent:** 4 Days
>
> **Total Cost:** 5sp 6cp (56% of cost)

### Bulk Crafting

Some items are cheap and easy enough to make that you may want to produce them in large quantities. Treat the combined value of those items as if they were a single item for determining total cost and crafting difficulty. Items can only be crafted in bulk if all items being produced are exactly the same.

If partial progress is enough to represent one or more complete items, treat those items as completed. This also means that fumbles can only cause you to lose progress only on the quantity of items still in progress.

> ##### Bulk Crafting Example
> ___
> **Item:** 10 Javelins
>
> **Cost:** 20sp (2sp × 10)
>
> **Difficulty:** 8
>
> | Roll | Progress | Cost |
> |:-:|:-:|:-:|
> | 13 (Success) | +20% = 20% | 3sp (75%) |
> | 17 (Critical) | +50% = 70% | 5sp (50%) |
> ___
> **Time Spent:** 2 Days
>
> **Total Cost:** 8sp (40% of cost)

In this example, 70% of ten javelins was crafted over two days. This translates to seven complete javelins (which can be used immediately), and prepared work for another three.

This progress can be resumed at a later date, leading us to the next example:

> ##### Bulk Crafting Example (Precrafted)
> ___
> **Item:** 10 Javelins
>
> **Precrafted:** 70%
>
> **Cost:** 20sp (2sp × 10)
>
> **Difficulty:** 8
>
> | Roll | Progress | Cost |
> |:-:|:-:|:-:|
> | - | 70% | - |
> | 8 (Success) | +20% = 90% | 3sp (75%) |
> | 1 (Fail) | -0% (-5%) = 90% | - |
> | 10 (Success) | +10% = 100% | 1sp 5cp (75%) |
> ___
> **Time Spent:** 3 Days
>
> **Total Cost:** 4sp 5cp (22.5% of cost)
>
> **Combined Total Cost:** 12sp 5cp (62.5% of cost)

You might notice that on the second of these last three days, that no progress was actually lost. This is because upon reaching 90% of the total progress the day before, another two whole javelins were crafted. Since there are no partially crafted javelins, progress could not be lost.

The maximum number of items that can be crafted at once is twenty, regardless of the percentage of crafting gained.

### Long-term Crafting

If you expect a craft project to take a large amount of time (upwards of 50 in-game days), rather than rolling 50 times, you may process the crafting in 6-day chunks. You do this by making a single crafting roll, then approximate the next 5 days with your average roll. This shortcut is only available if your average roll is less than the crafting difficulty, but not low enough to fail. To determine your average roll, take half your maximum craft roll, add any bonuses, then add 1 for every two dice you would roll.

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
> **Item:** Superior Platemail
>
> **Cost:** 150sp
>
> **Difficulty:** 16
>
> | Roll | Progress | Cost |
> |:-:|:-:|:-:|
> | 18 (Success) | +20% = 20% | 22sp 5cp (75%) |
> | Auto (Graze ×5) | +2% ×5 (10%) = 30% | 2sp 7cp (90%) ×5 (13sp 5cp) |
> | 12 (Graze) | +2% = 32% | 2sp 7sp (90%) |
> | Auto (Graze ×5) | +2% ×5 (10%) = 42% | 2sp 7cp (90%) ×5 (13sp 5cp) |
> | 16 (Success) | +20% = 62% | 22sp 5cp (75%) |
> | Auto (Graze ×5) | +2% ×5 (10%) = 72% | 2sp 7cp (90%) ×5 (13sp 5cp) |
> | 11 (Fail) | -5% = 67% | - |
> | Auto (Graze ×5) | +2% ×5 (10%) = 77% | 2sp 7cp (90%) ×5 (13sp 5cp) |
> | 15 (Graze) | +2% = 79% | 2sp 7sp (90%) |
> | Auto (Graze ×5) | +2% ×5 (10%) = 89% | 2sp 7cp (90%) ×5 (13sp 5cp) |
> | 17 (Success) | +11% (20%) = 100% | 12sp 4cp (75%) |
> ___
> **Time Spent:** 31 Days
>
> **Total Cost:** 130sp 3cp (86.9% of cost)

### Rushed Crafting

If speed is more important than cost you can rush your craft check, which you can also make while long-term crafting. Rushed crafting alters the precentage of progress made and how much it costs at each success category:

***Double Critical:*** Gain 100% progress paying 75% of the cost.  
***Critical:*** Gain 75% progress paying 75% of the cost.  
***Success:*** Gain 50% progress paying 90% of the cost.  
***Graze:*** Gain 5% progress paying 100% of the cost.  
***Fail:*** Lose 10% progress.

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
> **Item:** Superior Platemail
>
> **Cost:** 150sp
>
> **Difficulty:** 16
>
> | Roll | Progress | Cost |
> |:-:|:-:|:-:|
> | 18 (Success) | +50% = 50% | 67sp 5cp (90%) |
> | Auto (Graze x5) | +5% ×5 (25%) = 75% | 7sp 5cp (100%) ×5 (37sp 5cp) |
> | 12 (Graze) | +5% = 80% | 7sp 5cp (100%) |
> | Auto (Graze x4) | +5% ×4 (20%) = 100% | 7sp 5cp (100%) ×4 (30sp) |
> ___
> **Time Spent:** 11 Days
>
> **Total Cost:** 142sp 5cp (95% of cost)