---
Type: Player
Art: "![[Character Image Placholder]]"
Level: 0
AC: 0
Prof: 
HP: 0
HitDice: d0
Speed: 0
STR: 0
DEX: 0
CONST: 0
INT: 0
WIS: 0
CHA: 0
Race: RaceName
Alignment: NONE
Gender: GenderName
Age: "0"
Location: NONE
Class: ClassName
Subclass: SubClassName
AssociatedGroup: NONE
Likes: NONE
Dislikes: NONE
Pronouns: NONE
PersonalityTrait:
  - NONE
SocialTrait:
  - NONE
MentalTrait:
  - NONE
Proficiencies:
  - NONE
Resistances:
  - NONE
Languages:
  - NONE
DmgTkn: 0
TempHP: 0
Copper: 0
Silver: 0
Electrum: 0
Gold: 0
Platinum: 0
exampleProperty: Apprentice
---
>[!dice] %%FAKE TITLE HERE%%
>> [!dice] %%FAKE TITLE HERE%%  
>> # `=this.file.name`
>> ![[Character Image Placeholder]]
>> ###### Stats
>>  |
>> ---|---|
>> **Rank** |`INPUT[suggester(option(Novice), option(Apprentice), option(Veteran), option(Master)):exampleProperty]` |
>>  **Title** |`INPUT[text:Title]` |
>> **Reputation** | `3` |
>>  **HP** | `32` /32
>> **Aether** | `31` /31 |
>> **Stamina** | `29` /29 |
>> **Armor** | D4+3  |
>> **XP** | `VIEW[{xp}][text]`
>>  
>> ###### Weapons
| **Weapons** | **Type** | **Damage** | **Notes** |
| ---------------------- | ---------------- | --------------- | --------------- |
| Broad Sword (mastery)  | 2                | 3/2             | +2              |
| Dagger                 | 1                | 1/1             | +1              |
| Hand Axe               | 1                | 1/1             | +1              |
|                        |                  |                 |                 |
|                        |                  |                 |                 |
>> ###### Crafting Aspects
>| Air   | Bane | Boon | Chaos | Dark  | Death |
>| ----- | ---- | ---- | ----- | ----- | ----- |
>| `0`   | `0`  | `0`  | `0`   | `0`   | `0`   |
>| Earth | Fire | Life | Light | Power | Water |
>| `0`   | `0`  | `0`  | `0`   | `0`   | `0`   |
>###### Minerals
>
>| Coal | Iron | Silver | Aglite |
>| ---- | ---- | ------ | ------ |
>| `0`  | `0`  | `0`    | `0`    |
>>  ###### Currency
| **⟑-N**         | **⟑-A**         | **⟑-V**         | **⟑-M**         |
| -------------- | -------------- | ------------ | ---------------- |
| 0 | 0 | 0 | 0 |
>
>> [!infobox] Death Saves
>> ### Death Saves
| Success | <input type="checkbox" unchecked>  | <input type="checkbox" unchecked> | <input type="checkbox" unchecked> | 
| ------- | --- | --------------------------------- | --------------------------------- |
>>
| Fails | <input type="checkbox" unchecked>  | <input type="checkbox" unchecked> | <input type="checkbox" unchecked> | 
| ----- | --- | --------------------------------- | --------------------------------- |
>>
>> ### Skills
| Skill | Score       | Mod                     | Prof                              | ST                                  |
| ----- | ----------- | ----------------------- | --------------------------------- | ----------------------------------- |
| <font color="#ff0000">**STR**</font>   | `=this.STR` | +`=(this.STR - 10)/2`   | <input type="checkbox" unchecked> | +`=(this.STR - 10)/2`               |
| <font color="#ffff00">**DEX**</font>   | `=this.DEX`  | +`=(this.DEX - 10)/2`   | <input type="checkbox" unchecked> | +`=(this.DEX - 10)/2`               |
| <font color="#00b050">**CON**</font>   | `=this.CONST` | +`=(this.CONST - 10)/2` | <input type="checkbox" unchecked>   | +`=((this.CONST - 10)/2)` |
| <font color="#7030a0">**INT**</font>   | `=this.INT`          | +`=(this.INT - 10)/2`   | <input type="checkbox" unchecked>   | +`=((this.INT - 10)/2)`   |
| <font color="#245bdb">**WIS**</font>   | `=this.WIS`          | +`=(this.WIS - 10)/2`   | <input type="checkbox" unchecked> | +`=(this.WIS - 10)/2`               |
| <font color="#de7802">**CHA**</font>   | `=this.CHA`          | +`=(this.CHA - 10)/2`   | <input type="checkbox" unchecked> | +`=(this.CHA - 10)/2`               |
>> ### Skill Checks
| Ability               |                                   | Mod |
| --------------------- | --------------------------------- | --- |
| Acrobatics (DEX)      | <input type="checkbox" unchecked> | `1` |
| Animal Handling (WIS) | <input type="checkbox" unchecked> | +`=(this.WIS - 10)/2`  |
| Arcana (INT)          | <input type="checkbox" unchecked> | +`=((this.INT - 10)/2)`  |
| Athletics (STR)       | <input type="checkbox" unchecked> | +`=(this.STR - 10)/2`   |
| Deception (CHA)       | <input type="checkbox" unchecked> | +`=(this.CHA - 10)/2`  |
| History (INT)         | <input type="checkbox" unchecked> | +`=(this.INT - 10)/2`  |
| Insight (WIS)         | <input type="checkbox" unchecked>   | +`=((this.WIS - 10)/2)`  |
| Intimidation (CHA)    | <input type="checkbox" unchecked> | +`=(this.CHA - 10)/2`  |
| Investigation (INT)   | <input type="checkbox" unchecked>   | +`=((this.INT - 10)/2)`  |
| Medicine (WIS)        | <input type="checkbox" unchecked> | +`=(this.WIS - 10)/2`  |
| Nature (INT)          | <input type="checkbox" unchecked> | +`=(this.INT - 10)/2`  |
| Perception (WIS)      | <input type="checkbox" unchecked>   | +`=((this.WIS - 10)/2)`  |
| Performance (CHA)     | <input type="checkbox" unchecked> | +`=(this.CHA - 10)/2`  |
| Persuasion (CHA)      | <input type="checkbox" unchecked> | +`=(this.CHA - 10)/2`  |
| Religion (INT)        | <input type="checkbox" unchecked> | +`=(this.INT - 10)/2`  |
| Sleight of Hand (DEX) | <input type="checkbox" unchecked> | +`=(this.DEX - 10)/2`   |
| Stealth (DEX)         | <input type="checkbox" unchecked> | +`=(this.DEX - 10)/2`   |
| Survival (WIS)        | <input type="checkbox" unchecked> | +`=(this.WIS - 10)/2`  |