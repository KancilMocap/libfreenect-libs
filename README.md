# Prebuilt Libraries for libfreenect and libfreenect2

For libfreenect2, the libraries are built in the following configuration:
```
-- Feature list:
--   CUDA    no
--   CXX11    disabled
--   Examples    yes
--   OpenCL    no
--   OpenGL    yes
--   OpenNI2    yes
--   TegraJPEG    no
--   Threading    tinythread
--   TurboJPEG    yes
--   VAAPI    no
--   VideoToolbox    no (Apple only)
--   streamer_recorder    disabled
```

To have audio support, you would still need to install the required firmware based on the requirements at https://github.com/OpenKinect/libfreenect or https://github.com/OpenKinect/libfreenect2.
