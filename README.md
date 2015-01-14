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
- [ ] Interface displaying health
- [x] Way to attack enemies

Nice to have
------------

- [x] Scan directory and add textures automatically
- [x] Projectile
- [ ] Timed animations while walking
- [ ] Ladders (plain body that has isGround property, up key walks upwards)
- [ ] Potion to scare enemies so they run away (new behavior)
- [ ] Potion to make you fly for a time (fly behavior)
- [ ] Flying enemies
- [x] Trampoline
- [ ] Fall damage (character collision with speed above limit)
- [ ] Use background morph for repeating background
- [ ] Parallax background

Code quality
------------

- [ ] Use built in intersect function
- [ ] Return self instead of nothing for method chaining
- [ ] Use class side methods for constants
- [ ] Move depending on step time
- [ ] Consistently have negative velocity up
- [ ] Force subclass responsibility
- [ ] Correct parameter names in collision handles

Bugs
----

- [ ] Stop in air when something hits you from top
- [ ] Catch edge cases, e.g. load empty level, count number of unrecognized
      symbols, ...
- [ ] Remove mass from static bodies
- [ ] Prevent selecting button text, dispatch clicks on text upwards to button
