# clickForce
A clicking game. Gather gold and try to survive waves of enemies. 

Website: 
	Need to be able to sign in on the front page. Have a play button somewhere in the middle of the screen. If user is not logged in, it should ask the user if they want to sign in, sign up or play as a guest. At the end of a game, if player is not logged in prompt to log in or sign up to save their score. If not the score is dismissed. 

Database:
	Keep a database with tables for Users, High Scores, and Games. User database will contain info provided by the user at sign up, as well as a 'personal best' high score. High Scores will contain a list of the top 100 high scores in regards to: Most total gold earned(between all games played), Most gold earned in a signle game, longest total game time, longest single game time. Games table will contain data as needed for current games. 

Gameplay:
 -Click on an object to gain gold.
 -Spend gold on upgrades, repairs and ground forces to defend your object
 -Enemies will spawn periodically, slowly at first and then faster as the game progresses
 -Enemies will have to destroy your gate and capture your object to defeat you.
 -game ends when your object is taken by enemies.

 Under your control: 
 -You control a walled city with a gated entrance.
 -Gate has 100 hitpoints to start.
 -Buildings: 
    Shrine: Gives gold on click
    fletchers: produces archers at cost of gold
    barracks: produces soldiers at cost of gold
    stables: produces knights at cost of gold
    shamans hut: upgrades gold earned per click of the shrine at major cost of gold, increasing each time the upgrade is applied
    Blacksmith: upgrades damage of your units
    Carpenter: upgrades your buildings and gate at significant cost of gold

Opposing forces: 
 -enemies spawn from the top of the screen periodically, and move down the path toward your base. When they get to the gate they deal their damage to it. 
 -enemies will gain in strength and number as game progresses
 -new types of enemies will begin to spawn after certain periods of time. 
