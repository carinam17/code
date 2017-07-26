###Generate equally-spaced floats

Originally published: 2011-09-24 18:13:12
Last updated: 2011-09-24 18:49:39
Author: Steven D'Aprano

Generating a list of equally-spaced floats can surprising due to floating point rounding. See, for example, the recipe for a [floating point range](http://code.activestate.com/recipes/577068). One way of avoiding some surprises is by changing the API: instead of specifying a start, stop and step values, instead use a start, stop and count: