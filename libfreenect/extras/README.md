# Additional Instructions for Audio Support

The following instructions are copied from https://github.com/OpenKinect/libfreenect#fetch-buildt and https://github.com/OpenKinect/libfreenect/issues/376#issuecomment-41211251.

1. Include `ofxKinectExtras.cpp` and `ofxKinectExtras.h` in your project.
2. Call:
```
freenect_set_fw_address_nui(kinectContext, ofxKinectExtras::getFWData1473(), ofxKinectExtras::getFWSize1473());
freenect_set_fw_address_k4w(kinectContext, ofxKinectExtras::getFWDatak4w(), ofxKinectExtras::getFWSizek4w());
```
after `freenect_init()`.

This instructions do not cover firmware support for the earliest Kinect (1414). For more information, see https://github.com/OpenKinect/libfreenect#fetch-build.
