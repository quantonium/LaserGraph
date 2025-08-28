The Laser Games: https://store.steampowered.com/app/3152120/The_Laser_Games/

An important aspect of the game is communicating player statistics to users. Currently, there are only basic visuals, mainly tables, to show the results of the player. An additional in-map visual was developed last semester to show player positional data, 
visualizing data in 3D space, for th other visualization class.

This project proposes some UI visualization to show player generated data in The Laser Games. There is no set type of visualization yet for what the visualization will look like. 
Depending on the requirements of the class project, the visualization could either consist of multiple different small visualizations to showcase different aspects of the player's 
statistics over their play career and/or over a match; or, a detailed visualization to emphasize specific aspects of the player.

An optional requirement for this project, regarding utilization with The Laser Games, is to make a modular system able to be re-adapted to different Unreal Engine games and even projects beyond UE. Regarding tasks, the team behind The Laser Games will likely concern with the API with the engine and game, while the classmates would focus on developing the visuals themselves.

The following data is/can be provided to the visuals:

* per game (able to be saved per match, or shown at the end of a match)
  * hit info (list)
    * target
    * hit spot (front/back, weapon, etc.)
    * points
    * distance
    * start, end location
    * multiplier (num bounces)
    * time of hit
  * total shots
  * total distance
  * additional stats may be exposed depending on the requirements of the visualization
* player global
  * customizations (able to be changed at will by the player)
    * color
    * name
    * handedness
    * 1st/3rd person
    * additional future items able to be unlocked
  * global num shots, hits
  * num matches played
  * total distance
