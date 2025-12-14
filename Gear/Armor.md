# Armor

The DawnPiece mod has custom armor that drops from NPCs. As you progress through the story, you will be able to unlock the ability to fight a wider variety of characters that drop their own gear. Please see the information below to learn about how the custom gear works.

### Armor Stats

All armor will have a basic percentage for protection that mitigates damage. There are 6 Tiers for Gear: Common, Uncommon, Rare, Epic, Legendary and Mythical. You can increase the tier of the weapon by upgrading them at an upgrade table. There are no gear classes and every single piece will have a fixed percentage so you can mix and match pieces from different tiers to get a protection boost.<br> 
<br>
To create a noticeable difference between tiers at lower damage levels and prevent invincibility, we have introduced a Damage Reduction Floor (F) and Damage Thresholds. Thresholds are at the point where the actual percent and the floor protection are equal, so after this threshold is met the percentage will take over since it offers more protection. The equation and charts are below:<br> 
<br>
Protection = min(max(F,P), D−1)<br>
<br>
D: Incoming Damage<br>
F: Damage Floor Per Piece<br>
P: Damage Reduction Percent Per Piece<br>

| Tier      | Damage Reduction Per Set | Reduction Per Piece | Floor Per Piece |
|-----------|-------------------       |-------------------  |---------------  |
| Common    | 12%                      | 3%                  | 0.25            |
| Uncommon  | 20%                      | 5%                  | 0.50            |
| Rare      | 28%                      | 7%                  | 0.75            |
| Epic      | 40%                      | 10%                 | 1.00            |
| Legendary | 56%                      | 14%                 | 1.25            |
| Mythical  | 76%                      | 19%                 | 1.50            |

<div style="display: flex; gap: 12px; align-items: flex-start; justify-content: center;">
	<figure style="flex: 1; margin: 0;">
		<img src="/DawnPiece/Assets/Design/damage_chart_10.png" alt="Damage Floor Chart" style="max-width: 100%; height: 300px; object-fit: contain;" />
		<figcaption style="text-align: center; font-size: 0.9em; color: #666;">Damage Floor Chart</figcaption>
	</figure>
	<figure style="flex: 1; margin: 0;">
		<img src="/DawnPiece/Assets/Design/damage_chart_100.png" alt="General Damage Chart" style="max-width: 100%; height: 300px; object-fit: contain;" />
		<figcaption style="text-align: center; font-size: 0.9em; color: #666;">General Damage Chart</figcaption>
	</figure>
</div>

### Armor Upgrading

To upgrade your gear, you need to pay a certain amount of belly, have a certain amount of damage recieved with the armor, and insert the required upgrade orbs. These values are different depending on the armor tier, however if you place your armor inside the slot, the upgrade table interface will tell you what you need for the upgrade. Please see the following chart for a reference. Mythical armor cannot be upgraded since it is the final tier.

| Tier      | Damage Recieved   | Orb Needed    | Belly Cost    |
|-----------|-------------------|---------------|---------------|
| Common    | 1,000             | Uncommon (1x) | 4,000         |
| Uncommon  | 5,000             | Rare (2x)     | 20,000        |
| Rare      | 25,000            | Epic (3x)     | 100,000       |
| Epic      | 125,000           | Legendary (4x)| 500,000       |
| Legendary | 500,000           | Mythical (5x) | 2,500,000     |

### Armor Repairing

The durability of your amor is shown under the inventory icon, and the exact amount is shown in the tooltip when highlighting the armor in your inventory. Once the durability of the item reaches zero, it will not break however the armor will not provide any protection. You will see a message appear on your screen that tells you to repair your armor when it breaks.

Every time you are hit by an entity, the durability decreases by one. To repair gear, you must put your gear in a Repair Station found anywhere where there is a blacksmith in game. It will cost you 1 Belly to repair 10 durability. The cost always rounds up, so to repair 1-10 durability it will cost 1 Belly, 11-20 durability it will cost 2 Belly, and so on. You don't have to wait until durability reaches zero and can repair your armor anytime so it's best to do it before long battles.

| Tier      | Durability| Repair Cost at Zero|
|-----------|-----------|---------------|
| Common    | 400       | 40 Belly      |
| Uncommon  | 800       | 80 Belly      |
| Rare      | 1,600     | 160 Belly     |
| Epic      | 3,200     | 320 Belly     |
| Legendary | 6,400     | 640 Belly     |
| Mythical  | 12,800    | 1,280 Belly   |

### Gear Set Bonuses

All gear sets will have set bonuses when wearing every piece of the same set. If you mix and match different tiers in the same set, the set bonus will reflect the lowest tier bonus. The tooltip in game will show the set bonus you have. If you are not wearing pieces of the same set, the set bonus will say inactive. Weapons are not a part of the set bonus, only the four armor pieces are required. Please see the table below for the set bonuses we have in game.
