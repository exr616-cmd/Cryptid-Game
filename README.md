# Nocturne County V124 — Audio & Replayability

Final major feature package.

AUDIO:
- Master volume
- Music volume
- Ambience volume
- Dialogue volume
- Dynamic audio toggle
- Persistent audio settings

The intended dynamic audio architecture supports:
- Area ambience
- Cryptid-specific sound profiles
- Time-of-day layers
- Weather layers
- Combat music
- Stealth tension
- Supernatural distortion
- Silence events
- Character themes
- Major story stingers

REPLAYABILITY:
- 10-ending archive
- Cryptid identification tracker
- Memory tracker
- Location tracker
- Optional investigation tracker
- Secret discovery tracker
- Overall completion percentage
- Previously discovered ending names remain available while undiscovered
  endings stay hidden
- New Run / New Game Plus flag
- Discovered archive retained between runs

Replay philosophy:
The game should never reveal the solution to the mystery merely because the
player has completed it once. Previously discovered evidence can remain
available as a reference, but story knowledge still has to be interpreted by
the player.

100% completion is intended to mean:
- All 10 endings
- All 9 major cryptid classifications
- All major memories
- All county locations
- All optional investigations
- All secrets

Integration hook:
window.nocturneMarkReplay(type,id)

Types:
endings, cryptids, memories, locations, investigations, secrets

This completes the final planned major feature. Remaining work is integration,
story/content polish, balancing, testing, bug fixing, and final art/audio
assets.
