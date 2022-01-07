# Compressed Spatial Frequency Transfrom (CSFT)

CSFT is novel feature detection and description approach for robustly matching features across different views suitable for applications such as camera pose estimation and Structure-from-Motion in large scale aerial images. CSFT features are robust across a range of scale and rotation, image blur, varying illumination, and JPEG compression artifacts. The CSFT descriptor is compressed using geometric transformations in the frequency domain that significantly reduce its size. The CSFT feature uses a novel vectorized Normalized Cross Correlation (VNCC) method for matching descriptors. CSFT is a domain independent method that can be easily implemented. CSFT requires no training step compared to the deep learning approaches.  

## Library Dependencies   

- OpenCV C++ version 3.4.x
- CMake
- OpenMP

## Getting Started  

**Compiling**  

The following steps are required to compile the code.    

1. `$ mkdir build`
2. `$ cd build`
3. `$ cmake ..`
4. `$ make`  

