
# Mobile Robots

![Logo](https://www.laris.ufscar.br/@@site-logo/logoLARIS5English.svg)

This package works together with [MRS System](https://github.com/ctu-mrs/mrs_uav_system). It is a easy to simulate UAVs and Multi UAVs considering your real kinematics. 


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

  
## Installation 

Follow the instructions [here](https://github.com/ctu-mrs/mrs_uav_system) (on Installation tab)

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
  
## Optimizations

The next plans to this package is add the tutorial to add the sensor hokuyo.
  
## Related

This package is based on Petrobras Challenge package.

[Petrobras Challenge Package](https://github.com/LASER-Robotics/Petrobras_Challenge)

  
## Support

For support, email lidia@estudante.ufscar.br.

  
