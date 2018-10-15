# Build Recipe for OpenCV+Contrib for Python

Currently only builds for Windows. Support for Eigen is enabled, but CUDA,
OpenCL, VTK and OpenNI are disabled.

## Windows Status

* Python 3.6 for x64 works, I have not tried x86 because that requires a 32-bit
  (mini)conda installation.
* Python 2.7 fails because the VC 10.0 2010 does not support C++11 features
