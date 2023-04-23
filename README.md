# mh_amcl

Use combined with https://github.com/jmguerreroh/ros2_computer_vision.git

### Steps:
* Replace tiago_nav_params.yaml file:
```bash 
mv tiago_nav_params.yaml ros2_computer_vision/src/computer_vision/params/tiago_nav_params.yaml
```
* Launch simulation: 
```bash 
ros2 launch computer_vision sim.launch.py
```
* Launch mh_amcl navigation: 
```bash 
ros2 launch mh_amcl tiago_launch.py
```
