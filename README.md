# Turbo Turf Wars

## About the Project

Turbo Turf Wars is a fast-paced **local multiplayer game** designed for two players sharing the same computer. Players compete in real time to claim territory, block opponents, and control the map across best-of-three rounds.

This is the **first complete game I’ve built independently**, from concept to execution. The game was created as a single-file project, focusing on gameplay feel, simplicity, and replayability.

## Gameplay Overview

Players drive around a grid-based arena, painting tiles in their color by moving over them. At the end of each 75-second round, the player controlling more territory wins the round. Each match consists of up to three rounds.

Maps are procedurally generated each round with different wall layouts to keep strategies varied.

### Controls
- **Player 1:** W A S D  
- **Player 2:** Arrow Keys  

### Power-Ups
The game includes temporary power-ups such as speed boosts, area capture bombs, freezes, shields, and magnets that influence territory control and player movement.

## Technical Details

- Single HTML file (no build tools or dependencies)  
- Canvas-based rendering at 60 FPS  
- Written in vanilla JavaScript  
- Responsive layout for different screen sizes  

The full codebase is contained in one file and was iterated on to balance physics, collisions, power-ups, and visual feedback.

## How to Run

Open `turbo-turf-wars.html` in any modern browser and press **Space** to start.

## Credits

Created by **Shreyas Ramkumar**, 2026.
