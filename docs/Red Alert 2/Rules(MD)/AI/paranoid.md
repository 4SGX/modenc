# [Paranoid]

```ini
Paranoid=yes ; Boolean values: yes or no, true or false, 1 or 0 
```

This flag determines if all AI Houses within a game will ally against the human player(s) if the situation looks "bad" for them. Can be set to 'yes' or 'no'.
# In Tiberian Sun

If set, Paranoid causes the AI houses to ally if any of the following conditions is met:

    a hard AI (AI House with the highest possible IQ) is defeated
    a human player (or player controllable house) allies any non-MultiplayPassive house
    a human player leaves the game and the AI takes over

# In Red Alert 2 and Yuri's Revenge

If set, the effect is activated when two or more human players ally together. `Requires confirmation.`
# Bugs
This tag has two bugs. The first bug is only present in Tiberian Sun, when the AI will align with all neutral units on the map. This will also include Tiberium Mutants (VISSML, VISLRG, JFISH, and DOGGY). So it is not uncommon to see Visceroids casually passing through an AI base on a 'comp stomp' game! The second issue is in Red Alert 2 Version 1.004 and up, where the effects of the tag seem to have been made moot.