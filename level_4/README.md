#Level 4

You can hear bow strings being stretched.

Tip: No new abilities this time, but you must be careful not to rest while taking damage. Save a @health instance variable and compare it on each turn to see if you're taking damage.
```
 -------
|@ Sa S>|
 -------

  > = Stairs
  @ = Chugach (20 HP)
  S = Thick Sludge (24 HP)
  a = Archer (7 HP)
```

##Warrior Abilities

  `warrior.health`
    Returns an integer representing your health.

  `warrior.rest!`
    Gain 10% of max health back, but do nothing more.

  `warrior.feel`
    Returns a Space for the given direction (forward by default).

  `warrior.attack!`
    Attacks a unit in given direction (forward by default).

  `warrior.walk!`
    Move in the given direction (forward by default).


When you're done editing player.rb, run the `rubywarrior` command again.

* [Level 5](https://github.com/anchorageprogramming/rubywarrior/tree/master/level_5)
* [Level 3](https://github.com/anchorageprogramming/rubywarrior/tree/master/level_3)
