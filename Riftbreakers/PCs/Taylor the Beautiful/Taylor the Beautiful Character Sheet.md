---
exampleProperty: Novice
xp: 1450
PPCHP: 32
PPCMP: 31
PPCST: 29
Title: Protector of Kar Helos
Ring1: |
  Name: Champion's Ring of the Snake
  Magic: Dexterity +1, Reduce your Stamina pool by 5 (26), but increase your Aether pool by 8 (23). You no longer need to eat or drink.
  Aspects: Air Life 2x Boon Bane 
  Quirk: It's always pristine
  Value: 300A
Ring2: |
  Name: Mage's Wonderful Ring 
  Magic: Stamina +4, Stamina +4, On command, this item works as a source of light. Illuminates in a 20 m. radius.
  Value: 300A
  Aspects: Fire 2xPower Light 
  Quirk: It's always covered in a layer of mucus
Chest: Soft Leather D4 Integrity D6
Proficiencies: |-
  Weapons: Longbow, Scimitar
  Armor: Soft Leather
axp: 100
Other: |-
  Name: Knight's Glass Stone
  Magic: You can detect all living beings in a 20 m. radius. 
  Increase your luck by +5
  Rarity: Uncommon
  Rank: Novice
  Object: Other
  Identified
  Value: 200A
  Aspects: Chaos Life Boon Light
  Quirk: It appears to be completely made of glass. It doesn't make it more fragile than it should be though
Gloves: |-
  Name: Victorious Gloves of the Whisper 
  Aspects: Air Earth 
  Magic: Constitution +1 Charisma +1
  Rarity: Uncommon
  Rank: Novice
  Object: Gloves
  Value: 200A 
  Quirk: Smells like rotten flesh
Itemslotmax: 20
---
## Title  `INPUT[text:Title]`

---
## Rank `INPUT[suggester(option(Novice), option(Apprentice), option(Veteran), option(Master)):exampleProperty]`

---
```meta-bind-button
label: Add
icon: ""
style: primary
class: ""
cssStyle: ""
backgroundImage: ""
tooltip: ""
id: exp
hidden: True
actions:
- type: updateMetadata
  bindTarget: xp
  evaluate: True
  value: getMetadata('xp') + getMetadata('axp')

```
## Total XP : `VIEW[{xp}][text]`

ADD XP : `INPUT[number:axp]` `BUTTON[exp]`
## <span style="color:rgb(0, 176, 80)">HP</span>
```meta-bind
INPUT[progressBar(class(green-progress-bar), maxValue(32)):PPCHP]
```
## <span style="color:rgb(255, 105, 180)">Aether</span>
```meta-bind
INPUT[progressBar(class(pink-progress-bar), maxValue(31)):PPCMP]
```
## <span style="color:rgb(255, 128, 31)">Stamina</span>
```meta-bind
INPUT[progressBar(class(orange-progress-bar), maxValue(29)):PPCST]
```
## <span style="color:rgb(0, 176, 240)">Reputation</span>
` ` `3`
### [[Hearts & Abilities]]

---
## Stats

| **Strength**     | <center>10</center> | **Brawn**        | <center>50</center> | **Luck**        |   <span style="color:rgb(0, 176, 240)">5</span>   |
| ---------------- | ------------------- | ---------------- | :-----------------: | --------------- | :-----------------------------------------------: |
| **Dexterity**    | <center>16</center> | **Coordination** | <center>80</center> | **Armor**       | <span style="color:rgb(255, 128, 31)">D4+3</span> |
| **Constitution** | <center>18</center> | **Vitality**     | <center>90</center> | **Speed**       |                       15/30                       |
| **Will**         | <center>12</center> | **Tenacity**     | <center>60</center> | **Persistence** |                        65                         |
| **Intelligence** | <center>11</center> | **Intellect**    | <center>55</center> |                 |                                                   |
| **Charisma**     | <center>14</center> | **Charm**        | <center>70</center> |                 |                                                   |
| **STR Damage**   |                     | **DEX Damage**   |         +4          | **WIL Damage**  |                        +1                         |


---


|       **Weapons**        | **Type** | **Damage** |                 **Notes**                  |
| :----------------------: | :------: | :--------: | :----------------------------------------: |
| Holy Longbow of the Bear | Piercing |   2D6+4    | Two-handed, Holy, Arrows UD12, Range 115 m |
|         Scimitar         | Slashing |    D8+4    |               Parry, Finesse               |
|                          |          |            |                                            |

---
## Skills 

**Alchemy** (INT): `34`

**Acrobatics** (DEX):  `15`

**Animal Handling** (CHA): `14`

**Athletics** (STR): `33`

**Blacksmithing** (DEX): `35`

**Command** (CHA): `14`

**Gathering** (DEX): `57`

**Nature** (INT): `31`

**Literacy** (INT):  `54`

**Manipulation** (CHA): `14`

**Medicine** (INT): `11`

**Leatherworking** (DEX): `38`

**Insight** (WIL): `15`

**Dodge** (DEX): `75`

**Perception** (WIL): `32`

**Performance** (CHA): `14`

**Sailing** (DEX):  `15`

**Sleight of Hand** (DEX): `25`

**Stealth** (DEX): `38`

**Survival** (INT): `52`
## Gear
### Head
`INPUT[textArea:Head]`
### Chest
`INPUT[textArea:Chest]`
### Belt
`INPUT[textArea:Belt]`
### Pants 
`INPUT[textArea:Pant]`
### Boots
`INPUT[textArea:Boots]`
### Gloves
`INPUT[textArea:Gloves]`
### Ring 1
`INPUT[textArea:Ring1]`
### Ring 2
`INPUT[textArea:Ring2]`
### Pendant
`INPUT[textArea:Pendant]`
### Other
`INPUT[textArea:Other]`
### Proficiencies
`INPUT[textArea:Proficiencies]`
## Inventory

### Consumables

|  Rations  |  2   |
|:---------:|:----:|
| Lockpicks | Ud12 |
|    Oil    | Ud12 |
| Bandages  | Ud12 |
|  Torches  | Ud12 |
### Currency 

|  Type   | Amount |
| :-----: | :----: |
| **⟑-N** |  205   |
| **⟑-A** |        |
| **⟑-V** |        |
| **⟑-M** |        |

### Crafting Aspects

|  Air  |     |
| :---: | :-: |
| Bane  |     |
| Boon  |  1  |
| Chaos | 10  |
| Dark  | 11  |
| Death |  1  |
| Earth |  1  |
| Fire  | 11  |
| Life  |     |
| LIght | 16  |
| Power | 10  |
| Water | 10  |
|       |     |


| Air   | Bane | Boon | Chaos | Dark  | Death |
| ----- | ---- | ---- | ----- | ----- | ----- |
| `0`   | `0`  | `0`  | `0`   | `0`   | `0`   |
| Earth | Fire | Life | Light | Power | Water |
| `0`   | `0`  | `0`  | `0`   | `0`   | `0`   |



### Minerals

| Coal   | 20  |
| ------ |:---:|
| Iron   |  2  |
| Silver |  1  |
| Aglite |  4  |
### Notes




STR + 10 = `INPUT[number:Itemslotmax]`
### Item Slots

|  1  | Backpack                                                                                                                             |
|:---:|:------------------------------------------------------------------------------------------------------------------------------------ |
|  2  | Quiver                                                                                                                               |
|  3  | Torch Ud10                                                                                                                           |
|  4  | Bandage Ud12                                                                                                                         |
|  5  | Arrows Ud12                                                                                                                          |
|  6  | Rations x 2                                                                                                                          |
|  7  | Rough Leather x 10                                                                                                                   |
|  8  | Extra-Dimensional bag x 0                                                                                                            |
|  9  | Ascended Essence (Prime)                                                                                                             |
| 10  | Lantern                                                                                                                              |
| 11  |                                                                                                                                      |
| 12  | Aetheryte                                                                                                                            |
| 13  | Stoneskin Potion. For the next hour you have +1 Armor, but your Dodge and Acrobatics skills are reduced by -10. Aspects: Stone, Boon |
| 14  | Aetheryte                                                                                                                            |
| 15  |                                                                                                                                      |
| 16  |                                                                                                                                      |
| 17  |                                                                                                                                      |
| 18  |                                                                                                                                      |
| 19  |                                                                                                                                      |
| 20  |                                                                                                                                      |
| 21  |                                                                                                                                      |
| 22  |                                                                                                                                      |
| 23  |                                                                                                                                      |
| 24  |                                                                                                                                      |
| 25  |                                                                                                                                      |
| 26  |                                                                                                                                      |
| 27  |                                                                                                                                      |
| 28  |                                                                                                                                      |
| 29  |                                                                                                                                      |
| 30  |                                                                                                                                      |
| 31  |                                                                                                                                      |
| 32  |                                                                                                                                      |
| 33  |                                                                                                                                      |
| 34  |                                                                                                                                      |
| 35  |                                                                                                                                      |
| 36  |                                                                                                                                      |
| 37  |                                                                                                                                      |
| 38  |                                                                                                                                      |
| 39  |                                                                                                                                      |
| 40  |                                                                                                                                      |
