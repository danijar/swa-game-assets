Todos
=====

Major features
--------------

- [x] Working menu including keyboard support
- [x] Collectable coins
- [x] Door between levels
- [ ] Screen between levels showing statistics
- [x] Load levels from file
- [x] Multiple levels
- [ ] Interface displaying health
- [ ] Way to attack enemies

Nice to have
------------

- [x] Scan directory and add textures automatically
- [ ] Timed animations while walking
- [ ] Potion to scare enemies so they run away (new behavior)
- [ ] Potion to make you fly for a time (fly behavior)
- [ ] Flying enemies

Code structure
--------------

- [ ] Ask chair where to put helper functions like `createUniversalPath`
- [ ] Move set of pressed keys into window and provide `isKeyPressed`

Code quality
------------

- [ ] Use built in intersect function
- [ ] Return self instead of nothing for method chaining
- [ ] Use class side methods for constants
- [ ] Move dependent on step time
- [ ] Consistently have negative velocity up
- [ ] Force subclass responsibility

Bugs
----

- [ ] Stop in air when something hits you from top
- [ ] Catch edge cases, e.g. load empty level, count number of unrecognized
      symbols, ...
