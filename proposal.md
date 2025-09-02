## Info

The Laser Games: https://store.steampowered.com/app/3152120/The_Laser_Games/

An important aspect of the game is communicating player statistics to users. Currently, there are only basic visuals, mainly tables, to show the results of the player. An additional in-map visual was developed last semester to show player positional data, 
visualizing data in 3D space, for th other visualization class.

This project proposes some UI visualization to show player generated data in The Laser Games. There is no set type of visualization yet for what the visualization will look like. 
Depending on the requirements of the class project, the visualization could either consist of multiple different small visualizations to showcase different aspects of the player's 
statistics over their play career and/or over a match; or, a detailed visualization to emphasize specific aspects of the player.

An optional requirement for this project, regarding utilization with The Laser Games, is to make a modular system able to be re-adapted to different Unreal Engine games and even projects beyond UE. Regarding tasks, the team behind The Laser Games will likely concern with the API with the engine and game, while the classmates would focus on developing the visuals themselves.

## Data

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
 
## Data Processing

Data processing is a component of the objectives of the project, essentially developing an API to transfer data to the visualization medium. A simple data storage technique such as XML or JSON should function ideally, being simple enough to implement and utilize. Data being stored would consist mostly of numeric values, perhaps indexed by time or by multiple elements (such as multiple hits). Some string values might be used to identify players or as static data, such as chat messages.

## Objectives

* Develop a UI visualization framework for The Laser Games, allowing for dynamic visualizations of various game data in a
user-friendly manner
  * Identify ideal statistics to demonstrate the visualizations for the class project
  * Implement the visual in a way such that it can be loaded on a website
* Implement an API between the game and the visualization website, to allow for the dynamic data to be recorded and transferred
  * Implement in a manner which abstracts the API functionality away from dependency on the specific game, allowing it to be
applied to other projects without redesigning the API

## Must-have features

* visualization(s) for in-game data
* simple web interface to switch between different visualizations
* API to export data into a format able to be understood by visualization website
  * + technique to transfer data from game to visualization

## Optional features

* abstracted API to allow for reimplementation
* interactive visualizations able to show additional data from mouse, keyboard inputs
* showcasing the visualization interface in-game (or during gameplay, i.e. through the Steam UI)
* Data collection policies as needed, if uploading game data to a server is warranted


Visualization Design
