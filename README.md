Todos
=====

Major features
--------------

- [x] Working menu including keyboard support
- [x] Collectable coins
- [x] Door between levels
- [x] Screen between levels showing statistics
- [x] Load levels from file
- [x] Multiple levels
- [x] Way to attack enemies

Structure
---------

- [ ] Separate `World` from `LevelScreen`
- [ ] Add delta time and base speeds on it
- [ ] Input as behavior
- [ ] Correct y axis in velocity calculation
- [ ] Add level loader

Nice to have
------------

- [x] Scan directory and add textures automatically
- [x] Trampoline
- [ ] Interface displaying health
- [ ] Parallax background
- [ ] Timed animations while walking

Easy features
-------------

- [x] Projectile
- [ ] Fall damage (character collision with speed above limit)
- [ ] Flying enemies
- [ ] Ladders (plain body that has isGround property, up key walks upwards)
- [ ] Potion to scare enemies so they run away (new behavior)
- [ ] Potion to make you fly for a time (fly behavior)

Code quality
------------

- [ ] Use built in intersect function
- [ ] Return self instead of nothing for method chaining
- [ ] Use class side methods for constants
- [ ] Move depending on step time
- [ ] Consistently have negative velocity up
- [ ] Force subclass responsibility
- [ ] Correct parameter names in collision handles
- [ ] Rename `World` to `Level`

Bugs
----

- [ ] Stop in air when something hits you from top
- [ ] Catch edge cases, e.g. load empty level, count number of unrecognized
      symbols, ...
- [ ] Remove mass from static bodies
- [ ] Prevent selecting button text, dispatch clicks on text upwards to button
