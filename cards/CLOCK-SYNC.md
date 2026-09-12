# CARD: CLOCK-SYNC

- **id:** GGL-009
- **repo:** https://github.com/One-Wave-Universe/HEX-SPLIT (SYNC.md, clock_sync.py)
- **layer:** pipeline
- **one sentence:** one-wave-clock/1 — M4 commits phase; followers lock, hold, snap, or quit; no chromatic slew.
- **may touch:** HEX-SPLIT clock.json, BUCKET-R2 bars, GCAC polarity, GRAV-LAB M4 pair freeze
- **may not touch:** letting GPU dream packets commit, advancing phase on hold
- **falsifier:** phase moves when polarity is 0, or a follower catches up by walking +1
- **gate:** YELLOW
- **last kick:** 2026-09-12
