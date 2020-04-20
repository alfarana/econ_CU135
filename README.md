# Repository to process video multi-camera video using v4l2 driver for e-con systems CU_135 cameras

This code allow to record using multi-cameras, the code example use only 2 cameras.
If you want more cameras you only need add more camera objects in the code.

In order to execute the v4l2-multigrab you need to follow the next commands(Ubuntu):

 ./compilarMultigrab.sh (compilation file)

 ./v4l2setting.sh (file to control properties of the camera as saturation, expossure and so on)

 ./multigrab (executable)
