# Melt9 AR Menu - simple pizza + tall smoke, stronger shadow (v37)

Based on v36. No dome, no glass box, no cylinder - just
the pizza, appearing on the target photo, with real smoke.

Smoke (dishes/steam.png, BOSS's smoke2.jpg):
- Height 2x: smoke now rises from Y=-0.05 to Y=1.35
  (was 0.65), range 1.40 (was 0.70). Planes taller
  (0.80, was 0.55) and grows bigger as it rises
  (scale 0.7 to 1.6, was 1.4).
- Slower: 6.0-6.8 seconds per rise (was 3.8-4.6 s),
  so tall smoke rises slowly, like real smoke.
- Still cloudy and wavy: curls -18 to +18 degrees,
  sways +/- 0.12, starts low over the pizza face,
  stays on top while the pizza spins, tilts with
  the pizza from horizontal to vertical. Crossed
  planes, 5 wisps x 2, opacity 0.78.

Shadow (bottom of the pizza):
- Soft shadow: bigger (1.10 wide, was 0.95) and
  darker (opacity 0.65, was 0.45).
- Dark shadow inside: bigger (0.80, was 0.70) and
  darker (opacity 0.85, was 0.75).
  So the pizza looks grounded, even when tilted.

No smoke under the pizza in this version - smoke
rises UP from hot food, it does not go down. Smoke
under the pizza would look like burning, not fresh.

Kept: fixed AR label, Add to cart + Photo in AR,
1-second flash, auto-spin, self-hosted libs/ engine.
iOS (Quick Look) + Android (MindAR camera scan).
