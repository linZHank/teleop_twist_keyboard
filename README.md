# teleop_twist_keyboard
Generic Keyboard Teleop for ROS
> This is an modified version using WASD setting. For original teleop_twist_keyboard, please go to [here](https://github.com/ros-teleop/teleop_twist_keyboard)

## Launch
To run: `rosrun teleop_twist_keyboard teleop_twist_keyboard.py`

## Usage
```
Reading from the keyboard  and Publishing to Twist!
---------------------------
Moving around:
   u    w    e
   a    s    d
   z    x    c

For Holonomic mode (strafing), hold down the shift key:
---------------------------
   Q    W    E
   A    S    D
   Z    X    C

t : up (+z)
b : down (-z)

anything else : stop

=/- : increase/decrease max speeds by 10%
]/[ : increase/decrease only linear speed by 10%
./, : increase/decrease only angular speed by 10%

CTRL-C to quit
```

