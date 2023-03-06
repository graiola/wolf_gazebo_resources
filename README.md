# WoLF: Whole-body Locomotion Framework for quadruped robots

This repo contains a collection of various gazebo resources and worlds used with WoLF.

## Setup

See the documentation [here](https://github.com/graiola/wolf-setup/blob/master/README.md).

## How to add a new world

You can simply add a new world in the `worlds` folder, while the gazebo models can be placed in the `models` folder if needed.

To launch the world with WoLF:

`roslaunch wolf_controller wolf_controller_bringup.launch world_name:=new_world`

## Worlds

|   |   |   |   | 
|:-:|:-:|:-:|:-:|
| <figure> <img src="imgs/agriculture.jpg" width="200" height="150" /> <figcaption> agriculture </figcaption> </figure> | <figure> <img src="imgs/building.jpg" width="200" height="150" /> <figcaption> building </figcaption> </figure> | <figure> <img src="imgs/inspection.jpg" width="200" height="150" /> <figcaption> inspection </figcaption> </figure> |  <figure> <img src="imgs/maze.jpg" width="200" height="150" /> <figcaption> maze </figcaption> </figure>  |
| <figure> <img src="imgs/obstacle_avoidance.jpg" width="200" height="150" /> <figcaption> obstacle_avoidance </figcaption> </figure> |  <figure> <img src="imgs/office.jpg" width="200" height="150" />  <figcaption> office </figcaption> </figure>  | <figure> <img src="imgs/park_large.jpg" width="200" height="150" /> <figcaption> park_large </figcaption> </figure> |<figure> <img src="imgs/pyramid.jpg" width="200" height="150" /> <figcaption> pyramid </figcaption> </figure>   | 
|<figure> <img src="imgs/ruins.jpg" width="200" height="150" /> <figcaption> ruins </figcaption> </figure>  | <figure> <img src="imgs/stairs.jpg" width="200" height="150" /> <figcaption> stairs </figcaption> </figure> | <figure> <img src="imgs/postoffice.jpg" width="200" height="150" /> <figcaption> postoffice </figcaption> </figure> | <figure> <img src="imgs/rough_terrain.jpg" width="200" height="150" /> <figcaption> rough_terrain </figcaption> </figure> | 

### Note:

To be able to load the new models in gazebo you need to append the path to the `GAZEBO_MODEL_PATH`, for example:

`export GAZEBO_MODEL_PATH=$GAZEBO_MODEL_PATH:/your_path_to/wolf_gazebo_resources/models`

### Legal notes

 For the world descriptions all rights belong to their respective owners.
