Golf Pong
Game Description:

Golf Pong combines golf and the classic Pong game mechanics. The goal is to bounce the ball off paddles and guide it into the hole(past the other player's paddles). Players get a point when the ball ends up in the "hole." A player wins by getting to 5 points, once they do, they can restart the game. The game is engaging because each bounce changes the ball’s angle, requiring quick reactions and precision.

Technical Implementation:
Game Objects and Behaviors

Ball: Uses physics for bouncing and velocity changes. Includes random angle offsets to avoid repetitive paths.

Paddles: Controlled by the player. Collisions change the ball’s direction.

Walls/Boundaries: Keep the ball in play and limit angles.

Technical Requirements:

Ball uses Rigidbody2D and Collider2D for physics.

Paddles respond to Unity input for movement. I was required to change some default input settings programmed into Unity to allow two player control. 

Hole uses a trigger collider to detect win conditions.

Randomized bounce angles prevent endless loops.

Future Development Plan

Future updates could include higher difficulty game modes with higher speeds and more randomized bounce physics.

Possible mechanics: power-ups (larger paddles, speed boosts), hazards (wind zones, sticky surfaces), and scoring based on golf-specific rules or "strokes."

Themes could expand into courses like golf greens, city rooftops, or space arenas.

Development Reflection

The hardest part was adjusting ball physics and paddle physics to ensure that randomness and increased speed was occuring on each bounce because it was hard to tell if these were happening unless they are dramatically increased either way.

I learned how to use Rigidbody2D, collisions, and input handling in Unity. Next time, I would focus earlier on level variety and UI to improve polish.
None to Add
