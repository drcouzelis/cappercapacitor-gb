# cappercapacitor-gb

An original action platformer for the Game Boy

## Planning

- [ ] PICO-8
  - [ ] Animated sprite viewer
  - [ ] Art design
  - [ ] Gameplay test
    - [ ] Background and collision detection
    - [ ] Camera control

## Development

- [ ] Stage 1
  - [ ] Clean up code from the last game
  - [ ] New / temporary background tiles
  - [ ] Add meta-sprites
    - [ ] Capper
    - [ ] Look left and right, animated
  - [ ] Increase map size
    - [ ] Full size of VRAM
    - [ ] Camera follows player
    - [ ] Camera stops at edge of map
    - [ ] Update jump physics
  - [ ] Hazards
    - [ ] New sprites for lasers, saws, spikes
    - [ ] Update collision detection
  - [ ] Recreate stage from last game

## Ideas

- [ ] Look and feel
  - Large sprites
    - [ ] Capper 16x24
    - [ ] Dust 16x16
    - [ ] Sparks 8x8?
    - [ ] Lasers 8x whatever
    - [ ] No background elements smaller than 16x16
  - [ ] Digital cute
    - [ ] Cute Capper?
      - [ ] Bouncy, rounded, floppy top hat
    - [ ] Cute sparks?
    - [ ] Cute dust?
    - [ ] Cute backgrounds? Rounded corners? Big circles?
  - [ ] Colors
    - [ ] All sprites are black outlines, dark gray shading
    - [ ] Stage elements are black outlines, use white sparingly
    - [ ] All backgrounds white or light gray
- [ ] Hazards
  - [ ] Spikes
    - [ ] Floor
    - [ ] Ceiling
    - [ ] Walls
  - [ ] Lasers
    - [ ] Horizontal
    - [ ] Vertical
  - [ ] Sparks
    - [ ] Four frames of animation?
    - [ ] White with black outline?
    - [ ] Bouncing left / right
    - [ ] Bouncing up / down
    - [ ] Shooting horizontal / vertical
    - [ ] Bouncing diagonal
- [ ] Controls
  - [ ] Variable height jumps?
    - [ ] Tap for short jump, hold for high jump
  - [ ] Down to duck
- [ ] Collectables
  - [ ] Dust balls
    - [ ] Collect all to complete the stage?
    - [ ] Collect all for best score?
    - [ ] Adjacent dust forms a cohesive dust area?
- [ ] Health
  - [ ] One hit deaths
    - [ ] Stage resets completely?
      - [ ] If too challenging then the stage should be smaller / simpler?
  - [ ] No bosses
- [ ] 40 stages?
  - [ ] Mirror mode? Get from "end" to "start"?
  - [ ] Hard mode? Hazards move 2x speed?
