# [VeteranSpeed]

```ini
VeteranRatio=1.0    ; Floating point values
```

This is one of the several Veteran Factors that control the bonuses given by VeteranAbilities and EliteAbilities. VeteranSpeed is a straight multiplier to the Speed of units that benefit from the FASTER promotional bonus. Contrary to popular belief, these bonuses do not stack, meaning that a FASTER elite bonus will not further increase the maximum movement speed of a unit with a FASTER veteran bonus.  

# Example

if the unit's Speed is 5, then it would be increased to 6 (assuming VeteranSpeed=1.2).

    5 * 1.2 = 6.