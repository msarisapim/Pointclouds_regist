# Point Cloud Registration with Spatial and Color Data

## Overview
This project focuses on enhancing point cloud registration by integrating spatial (geometric) and color (intensity) information for improved alignment accuracy. Utilizing both spatial and color attributes allows for more precise alignments, beneficial in datasets with distinct color patterns.


## Methods (Same-source registration.ipynb)
- Colored ICP (Iterative Closest Point): Extends traditional ICP by incorporating color data.
- Generalized ICP (GICP) with Color: Integrates color information into the GICP framework.
- Joint Color and Depth (JCD) Descriptors: Utilizes a combination of color and depth data for registration.
  - Computation of JCD function.
  - Feature extraction and matching.
  - Transformation computation.
- Coherent Point Drift with Color (Colored CPD): Applies the CPD algorithm with an emphasis on color data.
- RANSAC with Color-based Descriptors: Leverages color features for the RANSAC algorithm.
- 4-Points Congruent Sets (4PCS) and Color Variants: Enhances 4PCS with color data for registration.
- Deep Learning Approaches: Investigates deep learning models like PointNetLK for registration tasks.
