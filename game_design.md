# 🐦 Project Name: Flappy Tube Runner (Double Trouble Edition)
**Game Design Document**

## 1. Visual Style
- **Background:** Light blue sky (`#87CEEB`) with parallax clouds.
- **Player Character:** Orange Cartoon Bird (Circular with beak/eye details).
- **Obstacles:** Dark Green Cylindrical Tubes with caps.
- **UI:** Life Counter (Hearts) and Score Counter.

## 2. Core Mechanics
- **Physics:** Gravity pulls down; Space Bar jumps (flaps).
- **Lives System:** - **Total Lives:** 2.
    - **Damage:** Hitting a tube removes 1 life.
    - **Invincibility:** After taking damage, the bird becomes temporary invincible (flashing) to allow recovery.
    - **Game Over:** Occurs when Lives reach 0 OR if the bird hits the ground (instant fail).
- **Fun Factors:**
    - Snappy physics (quick fall, strong jump).
    - Visual feedback when hit (Screen flash / Bird transparency).
    - Randomized tube heights.

## 3. Rules & Logic
- **Starting Position:** Bird spawns near the bottom-left.
- **Scoring:** +1 point for passing a tube.
- **Level Design:** Tubes are evenly spaced horizontally, but gaps vary vertically.

