# Changelog

## Improvements

- The player can now jump while moving into a wall, while still retaining the functionality of bumping their head against the ceiling 
- Increased player speed slightly from 3 to 4 
- Changed jumpDeceleration from 0 to 0.75, basically resulting in small hops being bigger, so the player can tap space to still make a useful jump 

## Additions

### Movement

- The player can cling to walls to descend more slowly
- The player can walljump (currently rough) with a 160ms grace period when they let go of a wall

### Combat

- The player has a gun to fire at enemies

### Gameplay

- The player new has a score, they earn 5 score for every enemy kill and 1 for every token picked up
- The level can only be finished if the player has at least 50 score

### UI

 - New HUD element to show score
 - New HUD element to explain the objective