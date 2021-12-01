# CS1666 InfRun Management weeks

1. 9/15 - 9/21
	* Manager: Caleb Kessler
	* Goals:
		1. Get project description and goals approved
1. 9/29 - 10/5
	* Manager: Dominic Karras
	* Goals:
		1. Create team credits sequence for the game
1. 10/6 - 10/19
	* Manager: Dane Halle
	* Goals:
		1. Simple movement demo encompassing "initial acceleration" to the right, standard jumping mechanics, and potentially capability for flipping.
			1.  Diagonal movement (down hill) 
			2.  API for vectors for later implementation
		2. Asset work for character and character animations, background asset(s), and ground tiling. 
		3. Advanced Topic Research
			1. Procedural gen: This team will do further research into our selected methods, being Perlin noise combined with Bezier curves. The ultimate goal will be an interface/outline for the API to be later implemented. 
			2. Physics engine: This team will do further research into rigid-body interactions as a whole as well as programming these simulations yourself. Similar interface/outline for the API to be later implemented. 
1. 10/20 - 10/26
	* Manager: Mateen Kasim
	* Goals:
		1. Entire team goals - PRIORITY
			1. Make framerate independent of hardware
				* Lock to 60fps
			2. Refactor game code to approach the gameplay we really want
				* Player is horizontally fixed on screen, while the terrain and background move around the player
				* Change the game from _really long_ runner to _infinite_ runner
				* Make the code more amenable to using procedurally generated terrain
		2. Advanced topic sub-team goals:
			1. Procedural gen: Get player movement to work when given non-linear terrain, e.g. simple random curves for hills
			2. Physics: Move all physics calculations into `physics.rs`, i.e. begin to fill out and utilize the Physics API skeleton from last week
		3. Presentations:
			* Physics outline due 10/27
1. 10/27 - 11/2
	* Manager: Elliot Snitzer
	* Goals:
		1. A simple "base game" will be demonstrated without the advanced topics implemented, including:
			a. Player Movement (jumping & flipping)
  			b. Game-ending collisions
  			c. Static obstacles (collision with static obstacles not necessarily generating static obstacles through procedural generation)
  			d. Collectible coins (coin collection as well as collision with coin objects still need to be implemented)
		2. Demonstrable backend progress towards implementation of procedural terrain generation.
		3. Demonstrable backend progress towards implementation of a physics engine.
		4. Physics research into how to implement several features to be described in our presentation (Ex: Rotation and how to calculate moments of inertia for 			   different objects, determination of endgame collisions using hitboxes or angle of terrain compared to angle of player upon landing)
		5. COMMENT ALL CODE AS MUCH AS POSSIBLE
1. 11/3 - 11/9
	* Manager: Michael Daley
	* Goals:
		1. Procedural Generation
			1. Begin Implementating last weeks backend work on Bezier Curves
			2. Procedural Generation Outline (due 11/8)
		2. Physics Engine
			1. Begin implementing the visualizations of last weeks backend work on collision resolution
			2. Implement Friction as a force 
			3. Implement acceleration up & down hills based on slope & constant friction
1. 11/10 - 11/16
	* Manager: Ben Ungar
	* Goals:
		1. Procedural Generation Team
			a. Fluid camera movement
			b. Chaining Bezier Curves
			c. Procedural Generation Slides (due 11/15)
		2. Physics Engine Team
			a. More precisely track and handle character positioning without ruining performance. Currently integers values are handling character position, need to shift to floating point values.
			b. Static obstacle collisions; for animating crashes before the end screen and also for non-game ending collisions.
		3. Other (contributors from Entire Team)
			a. Start on building the overall power up system. Only some backend structures and functions.
1. 11/17 - 11/30
	* Manager: NAME
	* Goals:
		1. Advanced terrain work
			1. New terrain types and visualizations of them 
				1. Asphalt (Lower friction)
				2. Sand (Higher friction)
				3. Water (Buoyancy) 	
			2. Physics handling of new terrain types
		2. Apply camera tracking to player's x velocity 
		3. Smooth bezeir curve implemented into the game's code instead of the simulation scene
		4. Variable jump with physics - Short press, short jump, long press, higher jump to cap out at some height
		5. Proper physics implementation of power ups instead of mostly hard coding
		6. Overhaul, clean up, and mass commenting of Proc Gen code
1. 12/1 - 12/7
	* Manager: Drew Wiesen
	* Goals:
		1. - Physics handling of new terrain types (continuation)
			-Asphalt, Sand and Water handling for friction differances and bouyancy 	 
		2. Fine tuning of control point generation 
			-Easier passing of control points from one TerrainSegment to another	 
		3. Pretty up UIs 
			-display score after game ends			
		4. Points given for actions (flips, etc)
			-Base points on distance travelled not time survivecd
			-Reward for significant action like flips
		5. QA Testing and fixes
