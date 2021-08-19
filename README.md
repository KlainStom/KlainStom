# KlainStom

### Ideas (in no particular order)
- Instance groups for consistent appearance (BossBars, SideBars, ...)
- Chat pools (chat messages are visible to all players on an instance of the same pool)
- Named instance wrapper (manage instances through names instead of or in addition to UUIDs)
- Resource pack "compiler" (merging all translations, custom textures, sounds, new items added by other extensions into one resourcepack and deliver it to the players)
- Game engine (essentially a method of creating games with multiple instances as a layer of abstraction on top of minestom)
- Save leave location (Players will join an instance where they left it)

### Project notes
- Resource pack "compiler" (merging all translations, custom textures, sounds, new items added by other extensions into one resourcepack and deliver it to the players)
  - based on:
    - minestom's resourcepack support
  - provides:
    - translations
    - additional sounds (named sounds)
    - additional item textures (textures with custom model data)


- Game engine (essentially a method of creating games with multiple instances as a layer of abstraction on top of minestom)
  - based on: 
    - Resource pack "compiler"
  - provides:
    - Instance groups for consistent appearance (BossBars, SideBars, ...)
    - Chat pools (chat messages are visible to all players of the pool or instance in the pool)
    - Named instance wrapper (manage instances through names instead of or in addition to UUIDs)
    - Save leave location (Players will join an instance where they left it)
    - Resource pack "compiler" (merging all translations, custom textures, sounds, new items added by other extensions into one resourcepack and deliver it to the players)
