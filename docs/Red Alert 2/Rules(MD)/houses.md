# [Houses]

The houses in TS, FS, RA2 and YR are all the available countries, playable and non-playable. In TS and FS there are only four houses;
```ini
0=GDI
1=Nod
2=Neutral
3=Special
```
However, in RA2 there are an additional nine;
```ini
0=Americans
1=Alliance
2=French
3=Germans
4=British

5=Africans
6=Arabs
7=Confederation
8=Russians
```
And in YR;
```ini
9=YuriCountry
```
is also added to the list bringing the total to fourteen. (The old four from TS are moved to the end of this list.)

This list should never be re-orded as this can result in game errors and crashes.

These listed houses are then listed under the Sides list in order to split them into their respective sides (Allied, Soviet, Yuri). In any of the unmodded games there is no way to add new houses that work exactly like the existing ones, however in TS and FS there is a workaround that allows you to add new houses. In YR you can also use the RockPatch to add new playable houses.

##### **Note:** In RA2 and YR, the Houses list is named the Countries list instead.

#

### [Houses] in rules(md).ini
In TS, this section listed all the playable countries. In RA2/YR, this section was renamed to [Countries], but the [Houses] is created and populated by the engine on-the-fly.

### [Houses] in Maps
Maps can define additional houses for their internal needs, as long as they specify which country they represent. The contents of this [Houses] section are appended to the rules' houses list, forming a zero-based numbered list, which is used by a lot of map Events and Actions. 