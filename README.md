# Golf Pong  

(https://play.unity.com/en/games/d7f01407-ebfc-4b24-b9c5-26099444c6ad/golf-pong)

## Game Description  
Golf Pong combines golf and classic Pong mechanics. The goal is to bounce the ball off paddles and guide it into the hole (past the other player's paddles). Players score a point when the ball ends up in the "hole." The first player to reach 5 points wins, and the game can then be restarted.  

The game is engaging because each bounce changes the ball’s angle, requiring quick reactions and precision.  

## Technical Implementation  

### Game Objects and Behaviors  
- **Ball**: Uses physics for bouncing and velocity changes. Includes random angle offsets to avoid repetitive paths.  
- **Paddles**: Controlled by the player. Collisions change the ball’s direction.  
- **Walls/Boundaries**: Keep the ball in play and limit angles.  

### Technical Requirements  
- Ball uses `Rigidbody2D` and `Collider2D` for physics.  
- Paddles respond to Unity input for movement. Some default Unity input settings were changed to allow two-player control.  
- Hole uses a trigger collider to detect win conditions.  
- Randomized bounce angles prevent endless loops.  

## Future Development Plan  
- Add higher difficulty modes with faster ball speeds and more randomized bounce physics.  
- Possible mechanics:  
  - Power-ups (larger paddles, speed boosts)  
  - Hazards (wind zones, sticky surfaces)  
  - Golf-inspired scoring (stroke-based system)  
- Expand themes into varied courses such as golf greens, rooftops, or space arenas.  

## Development Reflection  
The hardest part was adjusting ball and paddle physics to ensure randomness and speed changes were happening consistently. Small changes were often hard to notice unless dramatically increased. I also know that much of my design implementation took the longest method possible as oppose to using parents and children object to optimize time efficiency when designing the look and feel of the game.

I learned how to use `Rigidbody2D`, collisions, and input handling in Unity. Next time, I would focus earlier on level variety and UI improvements for a more polished experience.  
