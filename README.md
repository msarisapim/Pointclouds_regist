# Point Cloud Registration with Spatial and Color Data

## Overview

This project advances point cloud registration by combining spatial and color information, enhancing alignment accuracy, especially in color-rich datasets. It includes RGB-D data acquisition from cameras, notebooks for same-source registration, and experiments with SIFT for point cloud registration. The project utilizes the RGB-D Object Dataset and data from Intel Realsense cameras, showcasing methodologies like SIFT and comparing results with the FPFH method for precise and robust point cloud alignment.

## RGB-D Data acquisition from camera
- **RS_data_acquisition.ipynb**

## Point cloud registration
- **Same-source registration.ipynb**
- **Experiment on Point cloud registration using SIFT**
  - Experiment on dataset: **Arisa_PCRegist_SIFT-dataloop.ipynb**
  - Compare transformation result with fpfh method: **Arisa_PCRegist_SIFT-checkloopresults.ipynb**

## Dataset
- RGB-D Object Dataset : https://rgbd-dataset.cs.washington.edu/dataset/rgbd-dataset/
- RGB-D Data from Intel Realsense depth camera L515 and D435i
