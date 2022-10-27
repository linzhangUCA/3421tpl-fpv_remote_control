# First-Person View Remote Control 
Remotely control your robot to navigate from the entrance of LSCA 105 to the blue marker next to the south wall of the classroom. **You have to rely on the on-board camera to drive your robot.**

## Instructions: 
1. (10%) Complete `fpv_teleop_keyboard.py` to enable remote control on your robot using keyboard. 
Define keys associate with specific robot's movements (e.g., forward(),left(), right(), backward(), etc.).
   
2. (90%) Upload a video which records the first-person view navigation. Record the full navigation process: the robot start from the entrance of LSCA 105 and stops at the blue marker against the south wall.

#### Note
- VNC viewer is bad at streaming realtime video, so you may want to use `mjpeg_server.py` to stream video via a webserver.
- Carefully read line 3 to line 5 in `mjpeg_server.py` to figure out the usage.
- Drive your robot use the live streaming video. **DO NOT** follow your robot. 
- You may want to tweek the motor speed to get a more comfortable driving experience. 
- You can use any screen recording software to record the video.

## Helpful Resources
- Waveshare Motor Driver Board [Wiki Page](https://www.waveshare.com/wiki/RPi_Motor_Driver_Board).
- [gpiozero example](https://gpiozero.readthedocs.io/en/stable/recipes.html#robot) of driving a robot.
- [API](https://gpiozero.readthedocs.io/en/stable/api_boards.html#robot) for Robot class in gpiozero. 
- [pynput](https://pypi.org/project/pynput/) package.
- [picamera2 example](https://github.com/raspberrypi/picamera2/blob/main/examples/mjpeg_server.py) for hosting live stream video.
- [picamera2 manual](https://datasheets.raspberrypi.com/camera/picamera2-manual.pdf)
- [OBS (Open Broadcaster Software)](https://obsproject.com/) is a good screen recording software.
