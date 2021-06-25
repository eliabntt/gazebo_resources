# Gazebo models and worlds

[![License](https://img.shields.io/badge/license-GPLv3-blue)](https://opensource.org/licenses/GPL-3.0)

## How to Use

`models` directory contains various models
`world` directory contains various world configurations 
`photos` directory contains various screenshots for the world configurations

### Option 1 - easiest
To use these worlds you can simply set the path in your launch file/package.
With respect to the models you can copy the needed files (or all of them for simplicity) in the `.gazebo/models` folder.

### Option 2 - global paths

Adding `worlds` directory to the `GAZEBO_RESOURCE_PATH` environment variable. 


To do so, directly use the following command or add the following line to `~/.bashrc`:
```
export GAZEBO_RESOURCE_PATH=$GAZEBO_RESOURCE_PATH:<path to this repo>/worlds
```


For the models the environment variable of interest is `GAZEBO_MODEL_PATH`. Again, either locally run or add the following line to the end of `~/.bashrc`:

```
export GAZEBO_MODEL_PATH=$GAZEBO_MODEL_PATH:<path to this repo>/models
```

## Sources
 - [3DGEMS - seems no longer working](http://data.nvision2.eecs.yorku.ca/3DGEMS/)
 - [RotorS](https://github.com/ethz-asl/rotors_simulator)
 - [TU Delft](https://github.com/tudelft/gazebo_models)
 - [ARTI-Robots](https://github.com/ARTI-Robots/gazebo_worlds)
 - [Clearpath Robotics](https://github.com/clearpathrobotics/cpr_gazebo)
 - [Fetch Robotics](https://github.com/fetchrobotics/fetch_gazebo)
 - [AWS Robotics](https://github.com/aws-robotics/)
