---
base_level: 7
sorc_level: 5
war_level: 2
str: -2
dex: 2
con: 2
cha: 4
wis: -1
int: 1
prof: 3
base_armor: 13
rolled_hp: 41
speed: 29
Creator: Arpan Mukhoti
Universe: D&D
Campaign: Verdant Tales
Player: AS Naeem
Character: Yinro Belelor
---
%%
Creator:Arpan Mukhoti:
Universe:Verdant:
Campaign: Verdant Tales:
Adventure_Diary:Yinro:
%%
<i>**` dv= this.Creator`**
` dv= this.Universe`
` dv= this.Campaign`</i>


# <% tp.file.title %>
> (Description:: )

![[|locl+hs-med]] <i>[]()</i>

| **Class**      |     **Sorcerer**     |     **Warlock**     |
| -------------- | :------------------: | :-----------------: |
| **Level**      | `VIEW[{sorc_level}]` | `VIEW[{war_level}]` |
| **Race**       |        Human         |         Elf         |
| **Alignment**  |       Neutral        |        Good         |
| **Background** |         Sage         |     Researcher      |
# Senses
| Senses                    |  \#   |
| ------------------------- | :---: |
| **Passive Perception**    |   9   |
| **Passive Investigation** |  11   |
| **Passive Insight**       |   9   |
| **Darkvision**            | 60ft. |

# Stats

|                         HP                          |             AC             |      Speed      |  Initiative   | Hit DIce                                 | Bonus        | Temp HP |
| :-------------------------------------------------: | :------------------------: | :-------------: | :-----------: | ---------------------------------------- | :------------: | :-------: |
| `VIEW[{base_level}*{con}+{rolled_hp}+{sorc_level}]` | `VIEW[{base_armor}+{dex}]` | `VIEW[{speed}]` | `VIEW[{dex}]` | `=this.sorc_level`d6+`=this.war_level`d8 | `=this.prof` | 0       |
# Senses 

| Senses                    | \#     |
| ------------------------- | ------ |
| **Passive Perception**    | 9      |
| **Passive Investigation** | 11     |
| **Passive Insight**       | 9      |
| **Darkvision**            | 60 ft. |

## Abilities
### Abilities
| STR | DEX | CON | INT | WIS | CHA | \#               |
| :-: | :-: | :-: | :-: | :-: | :-: | ---------------- |
|  7  | 15  | 15  | 13  |  9  | 18  | **Stats**        |
| -2  | +2  | +2  | +2  | -1  | +4  | **Modifier**     |
| -2  | +2  | +5  | +1  | -1  | +7  | **Saving Throw** |


### Skills
|           Bonus           |      Skill       | Ability | Proficiency |
| :-----------------------: | :--------------: | :-----: | :---------: |
|       +`= this.dex`       |    Acrobatics    |   DEX   |      N      |
|       `= this.wis`        | Animal Handling  |   WIS   |      N      |
| +`= this.int + this.prof` |    **Arcana**    |   INT   |    **P**    |
|       `= this.str`        |    Athletics     |   STR   |      N      |
| +`= this.cha + this.prof` |  **Deception**   |   CHA   |    **P**    |
| +`= this.int + this.prof` |   **History**    |   INT   |    **P**    |
|       `= this.wis`        |     Insight      |   WIS   |      N      |
| +`= this.cha + this.prof` | **Intimidation** |   CHA   |    **P**    |
|       +`= this.int`       |  Investigation   |   INT   |      N      |
|       `= this.wis`        |     Medicine     |   WIS   |      N      |
|       `= this.wis`        |      Nature      |   WIS   |      N      |
|       `= this.wis`        |    Perception    |   WIS   |      N      |
|       +`= this.cha`       |   Performance    |   CHA   |      N      |
| +`= this.cha + this.prof` |  **Persuasion**  |   CHA   |    **P**    |
|       +`= this.int`       |     Religion     |   INT   |      N      |
|     +`= this.dex + 2`     | Sleight of Hand  |   DEX   |      N      |
| +`= this.dex + this.prof` |   **Stealth**    |   DEX   |    **P**    |
|       `= this.wis`        |     Survival     |   WIS   |      N      |

# Traits
## Proficiencies
- Light Armor
- Simple Weapons
## Languages
- Celestial
- Common
- Draconic
- Elvish
- Primordial
- Sylvan

# Actions
**Sorcerer Points:**<p><input type=checkbox><input type=checkbox><input type=checkbox><input type=checkbox><input type=checkbox><input type=checkbox><input type=checkbox></p>
#### Attack

- **Weapon Attacks Table**

| Weapon         |       Attack Bonus        | Damage/Type                | Range     |
| -------------- | :-----------------------: | -------------------------- | --------- |
| Light Crossbow | +`= this.dex + this.prof` | 1d8 + `=this.dex` piercing | 80/320 ft |
| Dagger         | +`= this.dex + this.prof` | 1d4 + `=this.dex` piercing | 20/60 ft  |
| Short Sword    | +`= this.dex + this.prof` | 1d6 + `=this.dex` slashing | Melee     |

#### Movement and General
- Dash, Disengage, Dodge, Help, Hide, Ready, Search, Use an Object
- [[#Backpack|Drink a Potion or Use an Item]]
- [[#Spells|Cast a Spell]]

#### Nethergrasp Abilities
- [[Items#^deathRay|Death Ray]]
- [[Items#^deathStench|Deathly Stench]]
- [[Items#^breathDeath|Breath of Death (Recharge 5-6)]]
# Bonus Actions
- Convert Spell Slots
- Create Spell Slots

| SPELL SLOT LEVEL | SORCERY POINT COST |
| :--------------: | :----------------: |
|       1st        |         2          |
|       2nd        |         3          |
|       3rd        |         5          |
|       4th        |         6          |
|       5th        |         7          |

# Reactions
- [[Spells#Hellish Rebuke|Hellish Rebuke]] (1st Level, Warlock)
- [[Spells#Shield|Shield]] (1st Level, Sorcerer)
- [[Spells#Counterspell|Counterspell]] (3rd Level, Sorcerer)
# Free Actions
- **Invoke Metamagic**
	- [[#Empowered Spell]]
	- [[#Heightened Spell]]
	- [[#Quickened Spell]]
	- [[#Twinned Spell]]

# Spells
### Spell Attack

| Stats        | Sorcerer | Warlock |
| ------------ | :------: | :-----: |
| Modifier     |    +4    |   +4    |
| Spell Attack |    +8    |   +7    |
| Save DC      |    16    |   15    |
### Spell Slots
- **1st Level:**
<p><input type=checkbox><input type=checkbox>Pact</p>
	<p><input     type =checkbox><input     type =checkbox><input     type =checkbox><input type=checkbox>Slots</p>
- **2nd Level:**<p><input     type =checkbox><input     type =checkbox><input     type =checkbox>Slots</p>
- **3rd Level:**
<p><input     type =checkbox><input     type =checkbox>Slots</p>
### Known Spells

| **Level** | **Name**                                  | **Time** | **Range** | **Hit / DC** | **Effect**       | **Notes**           |
| --------- | ----------------------------------------- | -------- | --------- | :----------: | ---------------- | ------------------- |
| Cantrip   | [[Spells#Control Flames\|Control Flames]] | 1 Action | 60 feet   |      -       | Control          | 5ft., S             |
| Cantrip   | [[Spells#Eldritch Blast\|Eldritch Blast]] | 1 Action | 120 feet  |      +7      | 1d10+`=this.cha` | Count: 2, V/S       |
| Cantrip   | [[Spells#Fire Bolt\|Fire Bolt]]           | 1 Action | 120  feet |      +8      | 2d10             | V/S/M               |
| Cantrip   | [[Spells#Mending\|Mending]]               | 1 Minute | -         |      -       | Utility          | V/S/M               |
| Cantrip   | [[Spells#Minor Illusion\|Minor Illusion]] | 1 Action | 30 feet   |      -       | Control          | 5ft., S/M           |
| Cantrip   | [[Spells#Shape Water\|Shape Water]]       | 1 Action | 30 feet   |      -       | Control          | 5ft., S             |
| Cantrip   | [[Spells#Mind Sliver\|Mind Sliver]]       | 1 Action | 60 feet   |    int 16    | 1d6 psychic      | D: 1Rnd, Special, V |

| **Level** | **Name**                                  | **Time**       | **Range** | **Hit / DC** | **Effect**     | **Notes**            |
| --------- | ----------------------------------------- | -------------- | --------- | :----------: | -------------- | -------------------- |
| 1         | [[Spells#Bane\|Bane]]                     | 1 Action       | 60 feet   |    wis 16    | Debuff         | D:10Min, Special, V  |
| 1         | [[Spells#Chaos Bolt\|Chaos Bolt]]         | 1 Action       | 120 feet  |      +8      | 2d8+3d6 random | Special, V/S         |
| 1         | [[Spells#Hellish Rebuke\|Hellish Rebuke]] | 1 Reaction     | 60 feet   |    dex 16    | 4d10 fire      | V/S                  |
| 1         | [[Spells#Hex\|Hex]]                       | 1 Bonus Action | 90 feet   |      -       | 1d6            | D:1Hr, Special, V/S  |
| 2         | [[Spells#Vortex Warp\|Vortex Warp]]       | 1 Action       | 120 feet  |    con 16    | Control        | Special, V/S         |
| 3         | [[Spells#Counterspell\|Counterspell]]     | 1 Reaction     | 60 feet   |      -       | Negation       | Special, S           |
| 3         | [[Spells#Fireball\|Fireball]]             | 1 Action       | 150 feet  |    dex 16    | 8d6 fire       | 20ft. V/S/M          |
| 3         | [[Spells#Slow\|Slow]]                     | 1 Action       | 120 feet  |    wis 16    | Control        | D: 1m, 40ft., V/S/MP |
|           |                                           |                |           |              |                |                      |

#### Sorcerer Spells
- [[Spells#Control Flames|Control Flames]] (Cantrip, Sorcerer): Action
- [[Spells#Shape Water|Shape Water]] (Cantrip, Sorcerer): Action
- [[Spells#Firebolt|Firebolt]] (Cantrip, Sorcerer): Action
- [[Spells#Mind Sliver|Mind Sliver]] (Cantrip, Sorcerer): Action
- [[Spells#Shield|Shield]] (1st Level, Sorcerer): Reaction
- [[Spells#Chaos Bolt|Chaos Bolt]] (1st Level, Sorcerer): Action
- [[Spells#Vortex Warp|Vortex Warp]] (2nd Level, Sorcerer): Action
- [[Spells#Counterspell|Counterspell]] (3rd Level, Sorcerer): Reaction
- [[Spells#Fireball|Fireball]] (3rd Level, Sorcerer): Action
- [[Spells#Slow|Slow]] (3rd Level, Sorcerer): Action

#### Warlock Spells
- [[Spells#Eldritch Blast|Eldritch Blast]] (Cantrip, Warlock): Action
- [[Spells#Minor Illusion|Minor Illusion]] (Cantrip, Warlock): Action
- [[Spells#Bane|Bane]] (1st Level, Warlock): Action
- [[Spells#Hellish Rebuke|Hellish Rebuke]] (1st Level, Warlock): Reaction
 
# Possessions
## Currencies
| CP  | SP  | GP  | PP  |
| :-: | :-: | :-: | :-: |
|  7  |  2  | 49  |  0  |
- 555 gold worth of gems
## Backpack
#### Equipment
- [[Items#Light Crossbow|Light Crossbow]]
- [[Items#Component Pouch|Component Pouch]]
- [[Items#Explorer's Pack|Explorer's Pack]]
- Expensive Clothes
- Black Clothes
- Magic Key to Granather's Tavern

#### Magic Items
- [[Items#Bloodwell Vial|Bloodwell Vial (Uncommon)]]
- [[Items#Nethergrasp|Nethergrasp]]

#### Consumables
- [[Items#Healing Potion|Healing Potion]] x1
- [[Items#Greater Healing Potion|Greater Healing Potion]] x1
- [[Items#Scroll|Scroll of Shield]] x1
- [[Items#Scroll|Scroll of Mage Armor]] x1
- [[Items#Scroll|Scroll of Burning Hand]] x1

## Companions
- Male Baby Ursa Polaris - 24 point training
# Personality
###### Personality Traits

###### Ideals

###### Bonds

###### Flaws

# Features
## Racial

## Class
### Sorcerer 
#### Metamagic
##### Empowered Spell
When you roll damage for a spell, you can spend 1 sorcery point to reroll a number of the damage dice up to your Charisma modifier (minimum of one). You must use the new rolls.

You can use Empowered Spell even if you have already used a different Metamagic option during the casting of the spell.

##### Heightened Spell
When you cast a spell that forces a creature to make a saving throw to resist its effects, you can spend 3 sorcery points to give one target of the spell disadvantage on its first saving throw made against the spell.

##### Quickened Spell
When you cast a spell that has a casting time of 1 action, you can spend 2 sorcery points to change the casting time to 1 bonus action for this casting.
##### Twinned Spell
When you cast a spell that targets only one creature and doesn't have a range of self, you can spend a number of sorcery points equal to the spell's level to target a second creature in range with the same spell (1 sorcery point if the spell is a cantrip).

To be eligible, a spell must be incapable of targeting more than one creature at the spell's current level. For example, *magic missile* and *scorching ray* aren't eligible, but *ray of frost* and *chromatic orb* are.

### Warlock
- **Eldritch Envocations:** 
	- Agonizing Blast: When you cast [[Spells#Eldritch Blast|Eldritch Blast]], add your Charisma modifier to the damage it deals on a hit.
	- Thief of Five Fates: You can cast [[Spells#Bane|Bane]] once using a warlock spell slot. You can't do so again until you finish a long rest.
## Feats
- **Metamagic Adept**