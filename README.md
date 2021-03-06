# Prebuilt Libraries for libfreenect and libfreenect2

For libfreenect, the libraries are built in the following configuration:
```
BUILD_AS3_SERVER:BOOL=OFF
BUILD_CPACK_DEB:BOOL=OFF
BUILD_CPACK_RPM:BOOL=OFF
BUILD_CPACK_TGZ:BOOL=OFF
BUILD_CPP:BOOL=ON
BUILD_CV:BOOL=OFF
BUILD_C_SYNC:BOOL=ON
BUILD_EXAMPLES:BOOL=ON
BUILD_FAKENECT:BOOL=ON
BUILD_OPENNI2_DRIVER:BOOL=OFF
BUILD_PYTHON:BOOL=OFF
BUILD_PYTHON2:BOOL=OFF
BUILD_PYTHON3:BOOL=OFF
BUILD_REDIST_PACKAGE:BOOL=ON
```

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

In addition, they are also build without Python support (`-DBUILD_PYTHON3=OFF` and `-DBUILD_PYTHON=OFF`)

To have audio support, you would still need to install the required firmware based on the requirements at https://github.com/OpenKinect/libfreenect or https://github.com/OpenKinect/libfreenect2.
