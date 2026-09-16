NL2 gets the physics right, but a wooden coaster in the sim doesn't sound like one. 
SROM fixes that. It's a single scene object that layers real wooden-coaster recordings 
on top of NL2's stock audio and drives every layer live from the train: how far it is 
from you, how fast it's going, how hard it's pulling, and what section it's on. Off-ride 
and on-ride each get their own mix. No park edits, nothing replaced.

Key features

Distance-based roar — four bands (close / mid / far / long) that hand off as the train approaches or leaves; plank slap up close, low rumble across the park.
Never sounds like a loop — each band is a pool of 2–3 recordings blended with random, drifting weights.
Speed-aware — pitch and level track the train; separate slow-crawl structure rumble; silent when stopped.
G-force events — at 2.5 g+: rumble burst, extended close roar, reverb tail for distant listeners, and a sub-bass layer underneath.
Screams — speed-gated ambient screams, drop screams from a crest detector, a randomized on-ride scream pool, and a pass-by whoop when a train rips past you.
Chain lift — chain bed only on lift sections, separate "catch" sound at engage, starts a half-second early like the real thing.
Brake release (new in 1.1) — air-brake hiss when a train is released after a full stop on a block or brake run; never in stations, never on lifts.
Multi-train, multi-lift — every train gets its own emitters; lifts and stations are detected automatically.
Distance realism — screams fade earlier than the roar and duck past 220 ft; everything is silent beyond 260 m.
Tunable — a gain parameter per layer on the object; every distance, threshold and fade is a named constant in the script.
