# [Name]

```ini
UIName=<none> ; Maximum 128 character string
```

# On Houses / Countries / ObjectTypes / SuperWeaponTypes / TeamTypes

Plain-text name of this object. Was used in games prior to Red Alert 2 to output the object's name. It is now largely superceded by UIName, as an approach with strings makes for easier localization.

In Tiberian Sun, cameos are without text. Name is written on these by the game.

Note that Final Alert 2 does not use Name to determine the names of TechnoTypes, but UIName as well like the game.

Name strings are truncated to 23 characters maximum regardless of how long of a string you enter. 

# In [General]

As with UIName, there is a Name flag at the beginning of the [General] section. Yet again, it seems to be of no use, however The Guide mentions how it was supposedly possible to use several rule*.ini (rule1.ini, rule2.ini, ...) files in RA, and then to differentiate between them by name. This was, however, never seen in use and was probably dropped in favor of differently named, overriding INIs. 

# In [Basic]

In maps, this flag specifies the map name as shown in the game. (In RA2/YR, .map maps ignore this value and take their name from the mission.ini or PKT files.)