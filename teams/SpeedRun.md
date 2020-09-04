# CS1666 Team SpeedRun

## Canonical game repo URL:

https://github.com/Speedrun-Game-Dev-Pitt-CS1666-Fall-2020/Speedrun

## Team Members
* Advanced Topic Subteam 1 (Physics System)
	* Robert Xu
		* Pitt ID: rox5
		* Github Username: RobertXu09
		* Personal Fork URL: https://github.com/RobertXu09/Speedrun
	* Spencer Miller
		* Pitt ID: sdm74
		* Github Username: spap975
		* Personal Fork URL: https://github.com/spap975/Speedrun
	* Ryan Yang
		* Pitt ID: rcy7
		* Github Username: ruzakiff
		* Personal Fork URL: https://github.com/Ruzakiff/Speedrun
* Advanced Topic Subteam 2 (Procedural Level Generation)
	* Ryan Durkoske
		* Pitt ID: rjd68
		* Github Username: ryandurkoske
		* Personal Fork URL: https://github.com/ryandurkoske/Speedrun
	* Connor Kalina
		* Pitt ID: cjk94
		* Github Username: cjk94
		* Personal Fork URL: https://github.com/cjk94/Speedrun
	* Andrew Francioni
		* Pitt ID: ajf109
		* Github Username: ajf109
		* Personal Fork URL: https://github.com/ajf109/Speedrun
* Advanced Topic Subteam 2 (Networking)
	* Jacob Musone
		* Pitt ID: jpm160
		* Github Username: jmusone
		* Personal Fork URL: https://github.com/jmusone/Speedrun
	* Carter Smith
		* Pitt ID: cas380
		* Github Username: cas380
		* Personal Fork URL: https://github.com/cas380/Speedrun
	* Alexander Pujols
		* Pitt ID: alp203
		* Github Username: alp203
		* Personal Fork URL: https://github.com/alp203/Speedrun
	* Lucas Chronister
		* Pitt ID: lpc17
		* Github Username: lpc17
		* Personal Fork URL: https://github.com/lpc17/Speedrun 

## Game Description
Our game is a 2D platformer in which multiple players race against each other to get to the finish line first. The concept is a race to the bottom of a cave for treasure, so rather than left-to-right the general direction of the race is from top-to-bottom. Each race will be procedurally generated, with platforms and obstacles placed to create a challenging yet still beatable course. A physics system will promote interactivity between both players with each other and players with the course.

## General Milestones

* Create a unique, standalone level each time players start a race in the game
* Allow for multiple players (2-4?) to play and interact with each other at the same time
* Create responsive platformer movement (arrow keys?) that is affected by physical interactions with the course and other players
...

## Advanced Topics

* Physics System
	* Players will be able to move their player character responsively through arrow keys
	* Players will not be able to move through each other or obstacles through a rigidbody system
	* Objects that can be moved (Players characters and possibly some obstacles) will have forces applied on them that reflect how they bump and move into each other as well as gravity
	...
* Procedural Level Generation
	* Implement basic cave generation
	* Coordinate with physics team to make sure course is completable/fun
	* Add different biomes/obstacles to terrain
	...
* Networking
	* Get the server and client working and talking to each other
	* Get at least 4 players on the same server and properly moving on each other's screen
	* Make sure other objects are also synced properly on each other's screen
	...
