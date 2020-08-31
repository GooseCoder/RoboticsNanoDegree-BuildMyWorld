# HOW TO INSTALL

1. Create a build folder
2. From inside that folder run the following command
```
$ cmake ../
```
3. Run the make command
```
$ make
```
4. Export the GAZEBO_PLUGIN_PATH variable
```
$ export GAZEBO_PLUGIN_PATH=$GAZEBO_PLUGIN_PATH:/<path to this project>/build 
```
5. From the root of the project run:
```
$ gazebo world/HomeFirstFloor
```
6. It should start gazebo with the project world and a welcome message should appear in the console at the program startup.