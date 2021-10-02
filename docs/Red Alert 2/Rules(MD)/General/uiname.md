# [UIName]

```ini
UIName=<none> ; Maximum 128 character string referring to an object in the string table
```

# Under [General]

Seems to have no effect.

# On TechnoTypes, Sides, and Countries

Specifies the (case-insensitive) name of the CSF string which contains this object's display name. 

# Example 
```ini
[E1]
UIName=Name:E1
```
Meaning: If the game is in any situation asked to output the name of the unit "E1", it will respond with whatever is put in Name:E1 in ra2(md).csf - "GI", in this case. 