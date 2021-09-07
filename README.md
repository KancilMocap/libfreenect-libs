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

In addition, both libraries are also built using the Python3 wrapper (`-DBUILD_PYTHON3=ON`).
