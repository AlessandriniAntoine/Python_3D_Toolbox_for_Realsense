# RealSense

This repository provides a set of Python scripts useful for 3D file processing, particularly for files obtained using Realsense depth cameras. It includes an *acquisition_realsense.py* file for capturing and recording with a Realsense camera, as well as a *functions* folder containing a collection of processing functions (point cloud, ply, pixels...) and a subfolder *utils* containing some other useful functions.

Thanks to this repository you should be able to:

- Filter point cloud (density, threshold, radius, ...) thanks (or not) to users interface. 
- Process point cloud (resize, center on image, color, ...).
- Cut point cloud by selecting a zone with an interface.
- Find the homography between two images.
- Determine and apply an HSV mask to a point cloud.
- ...

## Usage

To test the code, execute the Python script example.py:
```console
python3 example.py
```
All outcomes will be stored in the 'example/output' folder.

## Prerequisites

This repository has been created using Python 3.8.10. Using another version may result in some problems. 

Python libraries required for the entire repository:

```console
pip3 install numpy
pip3 install pymeshlab
pip3 install scipy
pip3 install matplotlib
pip3 install opencv-python
pip3 install pyrealsense2
pip3 install pyvista
pip3 install open3d
```

For additional information about Realsense with Python, visit: https://dev.intelrealsense.com/docs/python2

Authors: Thibaud Piccinali, Tinhinane Smail

Supervision: Paul Chaillou

Revision: Damien Marchal




