# Hot Pursuit
[Play link](https://play.unity.com/en/games/7c72a3ed-9006-4d4c-b23b-7d33dc800eaf/hot-pursuit)
	Hot pursuit is a 2d endless game that somewhat resembles “Jetpack Joyride”. As the player, you are a news helicopter following a police chase while avoiding birds, drones, and power lines. While in pursuit, you have to obtain coins to achieve a higher score. Users advance levels  after they meet certain coin thresholds such as 300, 800, 1500, etc. As you progress levels, obstacles spawn more frequently and move at a faster pace. Ultimately, the goal is to stay alive as long as possible and beat your previous high scores.
# What’s working?
- Player can move up and down by tapping or holding the space bar
- Scrolling background gives the effect that the player is following the chase
- Drone, coin, and eagle animations are implemented to give the game life
- Player colliding with drones, eagles, floor, or the electricity lines (not poles) ends the game
- Player explodes on collision
- Game over screen is implemented with a working restart button for easy replayability
- Level, score, and high score are displayed during gameplay
- When a coin threshold is reached, a level up panel is displayed to alert the user. A slowmo effect happens simultaneously to remedy player being distracted and dying because of the panel
- Random sprite obstacles spawn at random heights using “Obstacle Spawner”
- Once a coin is hit, +10 is added to the players score
- Particle effect for tire smoke is added to the cars in the chase
- Tires on the cars spin for added realism
- Police car has a lightbar that changes between blue and red for added realism
# Bugs
- Power lines spawn floating occasionally
- Power lines despawn too soon
- Obstacles and coins often spawn on top of each other
- If player dies during level up, restart button on game over screen doesn’t work
- Helicopter force is much slower on build than on local host
What’s left?
- Implement instruction and menu screen
- Fix bugs
- Implement pause menu
- Add more obstacle variety
- Incorporate game audio
- Fix helicopter force
- Clean up scripts
- Maybe make the high score based on level?
# How to Play: 
You're immediately live on the scene when starting! Hold the space bar to rise and release to descend. Collect coins to advance through levels and set a new high score. Dodge obstacles to keep your chopper in the air!

