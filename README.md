## Extending Space Invaders tutorial with PyGame
### Followed the awesome Space Invaders PyGame tutorial from Tech with Tim YouTube channel- https://www.youtube.com/watch?v=Q-__8Xw9KTM 
#### Things I added to make game more enjoyable
1. Split the enemy and player laser velocities
2. Added music to the game
3. Added items that 1 comes in randomly at every level
    * Health item - increments health + 10 upon colliding with player
    * Life item - add one life upon colliding with player
    * Special weapon - activates special weapon upon colliding with player - allows player to shoot 3 lasers at once - lasts only for 3 times player is hit by enemy

#### Requirements
python 3.8.X or higher

#### How to run this application
```
python -m venv python_env
source /path/to/python_env/bin/activate
pip install -r requirements.txt
cd /path/to/python_game/
python3 main.py
```

