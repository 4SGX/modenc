# [VeteranCombat]

```ini
VeteranRatio=1.0    ; Floating point values
```

This is one of the several Veteran Factors that control the bonuses given by VeteranAbilities and EliteAbilities.

Contrary to popular belief, these bonuses do not stack, meaning that a FIREPOWER elite bonus will not further increase the damage dealt by a unit with a FIREPOWER veteran bonus. 

# In Tiberian Sun

VeteranCombat is an additive multiplier to damage dealt by the object's Primary, Secondary, and, in case of EliteAbilities=FIREPOWER, Elite weapons.

    Damage * (1.0 + VeteranCombat)

Example: If the unit's weapon deals 100 base Damage, then the hit would be increased to 125 (assuming VeteranCombat=0.25).

    100 * (1.0 + 0.25) = 125

# In Red Alert 2

Similar to TS, except the math has been simplified. VeteranCombat is now a direct multiplier to the base Damage inflicted by the weapon(s) of objects that benefit from the FIREPOWER promotional bonus.

Example: If the unit's weapon deals 100 base Damage, then the hit would be increased to 110 (assuming VeteranCombat=1.1).

    100 * 1.1 = 110

## Bugs/Side-Effects/Unexpected Limitations
VeteranCombat has no effect if the weapon uses a sonic wave.