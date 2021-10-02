# [BuildingTypes]

```ini
[BuildingTypes]
0=BUILDING1
1=BUILDING2
2=BUILDING3
```

[BuildingTypes] in TS through YR defines an array of structures that exist in the game. By default, there are several errors in the default array that should be corrected by a modder to reference listed types by number in the list. See next section.

Note that structures can be loaded into the game even without being in this list, if they are referenced by a tag that points to a BuildingType. For example, setting PrismType=ATESLA is enough to assure ATESLA will be loaded as a valid structure even without being in this array. However, this is not a good idea - such objects have no guaranteed load order, so you cannot be sure what index to address them by. 

---

## The corrected BuildingTypes arrays

Westwood messed up a lot of object arrays in the rules(md).ini. While this proved no problem for them, due to their map editor, which was built to parse the INIs the same way RA2 did, and was actually usable unlike FinalAlert, and their AI Editor, this can cause a lot of problems for modders that write all their scripts by hand.

I have previously posted the corrected Animations array for YR, and now I'm posting the corrected BuildingTypes arrays as well. When you write AI scripts, you can just use the exact number on the left of the building, no need to do funky +1 conversions (131072 in fact does affect the functionality, see [Corrected BuildingTypes Arrays](corrected-buildingtypes-arrays.md)).