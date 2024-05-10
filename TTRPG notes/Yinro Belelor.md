---
base_level: 6
sorc_level: 5
war_level: 1
str: -2
dex: 2
con: 2
cha: 4
wis: -1
int: 1
prof: 3
base_armor: 13
rolled_hp: 34
speed: 30
Creator: Arpan Mukhoti
Universe: D&D
Campaign: Verdant Tales
Player: AS Naeem
Character: Yinro Belelor
---


%%
Creator:Arpan Mukhoti: dfgdf
Universe:Verdant: gdfgd
Campaign: Verdant Tales: fgdfg
Adventure_Diary:Yinro: dfgdfg
%%
<i>**` dv= this.Creator`**
` dv= this.Universe`
` dv= this.Campaign`</i>


# <% tp.file.title %>
> (Description:: )

![[|locl+hs-med]] <i>[]()</i>

| **Class** | **Sorcerer** | **Warlock** |
| --------- | :----------: | :---------: |
|**Level** | `VIEW[{sorc_level}]`|`VIEW[{war_level}]`|
|**Race** | Human | Elf |
|**Alignment** | Neutral | Good |
|**Background** | Sage | Researcher |
# Senses
| Senses                    |  \#   |
| ------------------------- | :---: |
| **Passive Perception**    |   9   |
| **Passive Investigation** |  11   |
| **Passive Insight**       |   9   |
| **Darkvision**            | 60ft. |

# Stats

|                         HP                          |             AC             |      Speed      |  Initiative   | Hit DIce                                 | Bonus        | Temp HP |
| :-------------------------------------------------: | :------------------------: | :-------------: | :-----------: | ---------------------------------------- | ------------ | ------- |
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
Bonus | Skill | Ability | Proficiency |
:--:|:-----:|:------:|:-----:|
+`= this.dex` | Acrobatics | DEX |
`= this.wis` | Animal Handling | WIS | 
+`= this.int + this.prof` | **Arcana** | INT | **P**
`= this.str` | Athletics | STR |
+`= this.cha + this.prof` | **Deception** | CHA | **P**
+`= this.int + this.prof` | **History** | INT | **P**
`= this.wis` | Insight | WIS |
+`= this.cha + this.prof` | **Intimidation** | CHA | **P**
+`= this.int` | Investigation | INT |
`= this.wis` | Medicine | WIS |
`= this.wis` | Nature | WIS |
`= this.wis` | Perception | WIS |
+`= this.cha` | Performance | CHA |
+`= this.cha + this.prof` | **Persuasion** | CHA | **P**
+`= this.int` | Religion | INT |
+`= this.dex + 2` | Sleight of Hand | DEX |
+`= this.dex + this.prof` | **Stealth** | DEX | **P**
`= this.wis` | Survival | WIS |




# Traits




## Proficiencies

## Languages


# Actions

#### Attack
- **Weapon Attacks Table**
    - |Weapon|Attack Bonus|Damage/Type|Range|
        |---|---|---|---|
        Light Crossbow|+5|1d8 + `=this.dex` piercing|80/320 ft|
        Dagger|+5|1d4 + `=this.dex` piercing|20/60 ft|
        Short Sword|+5|1d6 + `=this.dex` slashing|Melee|

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



# Spells
| Stats        | Sorcerer | Warlock |
| ------------ | :------: | :-----: |
| Modifier     |    +4    |   +4    |
| Spell Attack |    +8    |   +7    |
| Save DC      |    15    |   16    |
#### Cantrips
| **Name**                                                       | **Time** | **Range** | **Hit / DC** | **Effect**  | **Notes**         |
| -------------------------------------------------------------- | -------- | --------- | :----------: | ----------- | ----------------- |
| [[Spells#Control Flames\|Control Flames]]                      | 1 Action | 60 feet   |      -       | Control     | 5ft., S           |
| [[Spells#Eldritch Blast\|Eldritch Blast]]                      | 1 Action | 120 feet  |      +7      | 1d10        | Count: 2, V/S     |
|  [[Spells#Fire Bolt\|Fire Bolt]]           \| 1 Action \| 120  et  |      +7      | 2d10        | V/S               |
| [[Spells#Mending\|Mending]]               | 1                                         |      -       | Utility     | V/S/M             |
| [[Spells#Minor Illusion\|Minor Illusion]] | 1 Action | 30 fe                      t   |      -       | Control     | 5ft., S/M         |
| [[Spells#Shape Water\|Shape Water]]       | 1 Action |                            t   |      -       | Control     | 5ft., S           |
| [[Spells#Mind Sliver\|Mind Sliver]]       | 1 Action |                            t   |    int 16    | 1d6 psychic | D: 1Rnd, SpecialV |

#### 1st Level  <p><input type=checkbox>Pact</p><p><input     type =checkbox><input     type =checkbox><input     type =checkbox><input type=checkbox>Slots</p>

| **Name**                                          | **Time**   | **Range** | **Hit / DC** | **Effect**  | **Notes**    |
| ------------------------------------------------- | ---------- | --------- | :----------: | ----------- | ------------ |
| [[Spells#Dissonant Whispers\|Dissonant Whispers]] | 1 Action   | 60 feet   |    wis 15    | 3d6 psychic | V            |
| [[Spells#Hellish Rebuke\|Hellish Rebuke]]         | 1 Reaction | 60 feet   |    dex 15    | 2d10 fire   | V/S          |
| [[Spells#Magic Missile\|Magic Missile]]           | 1 Action   | 120 feet  |      -       | 1d4+1 force | V/S          |
| [[Spells#Shield\|Shield]]                         | 1 Reaction | Self      |      -       | Warding     | D: 1Rnd, V/S |


#### 2nd Level <p><input     type =checkbox><input     type =checkbox><input     type =checkbox>Slots</p>

| **Name**                                          | **Time**   | **Range** | **Hit / DC** | **Effect**  | **Notes**     |
| ------------------------------------------------- | ---------- | --------- | :----------: | ----------- | ------------- |
| [[Spells#Dissonant Whispers\|Dissonant Whispers]] | 1 Action   | 60 feet   | wis 15       | 4d6 psychic | V             |
| [[Spells#Hellish Rebuke\|Hellish Rebuke]]         | 1 Reaction | 60 feet   | dex 15       | 3d10 fire   | V/S           |
| [[Spells#Magic Missile\|Magic Missile]]           | 1 Action   | 120 feet  | -            | 1d4+1 force | Count: 4, V/S |

#### 3rd Level <p><input     type =checkbox><input     type =checkbox>Slots</p>
| **Name**                                          | **Time**   | **Range** | **Hit / DC** | **Effect**  | **Notes**     |
| ------------------------------------------------- | ---------- | --------- | :----------: | ----------- | ------------- |
| [[Spells#Counterspell\|Counterspell]]             | 1 Reaction | 60 feet   | -            | Negation    | Special, S    |
| [[Spells#Dissonant Whispers\|Dissonant Whispers]] | 1 Action   | 60 feet   | wis 15       | 5d6 psychic | V             |
| [[Spells#Fireball\|Fireball]]                     | 1 Action   | 150 feet  | dex 15       | 8d6 fire    | 20ft. V/S/M   |
| [[Spells#Hellish Rebuke\|Hellish Rebuke]]         | 1 Reaction | 60 feet   | dex 15       | 4d10 fire   | V/S           |
| [[Spells#Magic Missile\|Magic Missile]]           | 1 Action   | 120 feet  | -            | 1d4+1 force | Count: 5, V/S |

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
- [[Spells#Dissonant Whispers|Dissonant Whispers]] (1st Level, Warlock): Action
- [[Spells#Hex|Hex]] (1st Level, Warlock): Bonus Action
 
# Possessions
## Currencies
|CP | SP | GP | PP |
|:---:|:---:|:---:|:---:|
|7|2|129|0|

## Backpack
#### Equipment
- [[Items#Light Crossbow|Light Crossbow]]
- [[Items#Component Pouch|Component Pouch]]
- [[Items#Explorer's Pack|Explorer's Pack]]

#### Magic Items
- [[Items#Bloodwell Vial|Bloodwell Vial (Uncommon)]]
- [[Items#Nethergrasp|Nethergrasp]]

#### Consumables
- [[Items#Healing Potion|Healing Potion]] x1
- [[Items#Greater Healing Potion|Greater Healing Potion]] x1
- [[Items#Scroll|Scroll of Shield]] x1
- [[Items#Scroll|Scroll of Mage Armor]] x1
- [[Items#Scroll|Scroll of Burning Hand]] x1



# Personality
###### Personality Traits

###### Ideals

###### Bonds

###### Flaws

