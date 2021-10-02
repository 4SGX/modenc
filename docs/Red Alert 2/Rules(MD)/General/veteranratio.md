# [VeteranRatio]

```ini
VeteranRatio=3.0    ; Floating point values (Defaults to 10 in TS, 5 in FS, and 3 in RA2)
```

This flag determines how many times the own value in credits a unit must destroy more than in order to be promoted. It is based on the Cost= values of objects and a straight multiplier. Note that this isn't limited to enemy objects. Civilian/Neutral, as well as your very own objects when Temporal=yes weapons are involved, count too.

Note the actual promotion only happens AFTER a unit has destroyed MORE than VeteranRatio * Cost=. 

# Example

The default setting for VeteranRatio is 3.0, the default price for a GI is 200 and the default price for a Conscript is 100. Therefore, in order to gain veterancy, a GI would have to destroy objects worth 200 * 3.0 + 1 == 601 credits for a promotion of one level. That could be, for example, more than six Conscripts, more than one Robot tank, or more than two Flak Troopers. The Conscript, however, only has to destroy 100 * 3.0 + 1 == 301 credits worth of objects to get promoted, meaning more than two GIs would be enough.

As you'll surely recognize, this means two things:

1. Destroying an expensive object with a cheap unit results in a very high chance of instant or very soon promotion.
2. Expensive units need to destroy a lot of stuff to get promoted (1 Prism Tank --> $1200 * 3.0 + 1 == $3601 == at least 37 Conscripts).

# Exceptions

Objects flagged as DontScore=yes or Insignificant=yes do not count as kills, and therefore don't add to the total amount of credits destroyed by a unit. As such, they don't bring them closer to promotion.