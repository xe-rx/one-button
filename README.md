Game in development for DT2020 at Nanyang Technological University. Still a concept.

# One Button Tower Defense

## Overview
A one-button tower defense game with a fixed enemy route and endless waves.  
The challenge comes from precise timing as a cycling cursor highlights plots of land and card choices.

## Cursor
- Cycles over **all interactive elements** (plots with or without towers, and between-round cards).  
- Cards reveal **iteratively each cursor cycle**, meaning players may have to commit early or risk missing better options.  
- Timing is key: the cursor’s alternation is synced with a **ticking sound** woven into the soundtrack.  
- Optional **screen flash** for visual timing cues (black & white pixel aesthetic).

## Towers
1. **Level 1:** Archer  
2. **Level 2:** Three Archers + range increase  
3. **Level 3:** Bomber (slightly less range than Level 2, but splash attack)

## Waves
- **Endless**: health scales slowly and caps, enemy count keeps increasing.  
- Needs careful balancing in B&W pixel art to avoid enemies blending together.  
- Possible fix: larger splash radius or visual tweaks for enemy distinction.

## Strategic Layer
- Between rounds, **3 random cards** appear; cursor cycles over them.
- Press to select the currently highlighted card.
- Choices can enhance towers, alter the route, or change economy.

