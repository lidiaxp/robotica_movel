
# Mobile Robots

![Logo](https://www.laris.ufscar.br/@@site-logo/logoLARIS5English.svg)

This package works together with [MRS System](https://github.com/ctu-mrs/mrs_uav_system). It is a easy to simulate UAVs and Multi UAVs considering your real kinematics. Some extra files to this package are in [Extra Files Package](https://github.com/lidiaxp/extraFilesRobotics).


## Build Status

| Component                                                   | 18.04                                                                                                                                       | 20.04                                                                                                                                      |
|-------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------|
| [robotica_movel](https://github.com/ctu-mrs/mrs_uav_system) | [![Build Status](https://github.com/ctu-mrs/mrs_uav_system/workflows/Melodic/badge.svg)](https://github.com/ctu-mrs/mrs_uav_system/actions) | [![Build Status](https://github.com/ctu-mrs/mrs_uav_system/workflows/Noetic/badge.svg)](https://github.com/ctu-mrs/mrs_uav_system/actions) |

## Features

- Multi UAV
- RPLidar
- Velodyne
- Rangefinder
- Bluefox
- Real-sense D-435
- Hokuyo

  
## Installation 

Follow the instructions [here](https://github.com/ctu-mrs/mrs_uav_system) (on Installation tab) to install MRS System

```bash 
  cd ~/workspace/src
  git clone https://github.com/lidiaxp/robotica_movel.git
  catkin build
  bash ../devel/setup.bash
```
To add the directory to models and worlds:

- Open gazebo
- Click on "Insert" (upper left)
- Click "Add Path" (upper left)
- Choose the paste ~/workspace/src/robotica_movel/models
- Close gazebo



    
## Running Tests

To run tests, run the following command

```bash
  cd
  bash ~/workspace/src/robotica_movel/src/start/start.sh
```

To run Multi UAVs run

```bash
  cd
  bash ~/workspace/src/robotica_movel/src/start/multiStart.sh
```
  
## Extras
### Add Hokuyo
To add hokuyo the instructions are in [Extra Files Package](https://github.com/lidiaxp/extraFilesRobotics) on "Add Hokuyo" tab.

### Solve "reference validation failed" error
when you run the project for the first time, an error similar to  "reference validation failed". If this occour the way to solve is in [Extra Files Package](https://github.com/lidiaxp/extraFilesRobotics) on "Solve 'reference validation failed'" tab.
  
  
## Related

This package is based on Petrobras Challenge package.

[Petrobras Challenge Package](https://github.com/LASER-Robotics/Petrobras_Challenge)

  
## Support

For support, email lidia@estudante.ufscar.br.

  
