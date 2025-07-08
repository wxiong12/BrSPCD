# Bridge Sonar Point Cloud Dataset (BrSPCD) Version_1.0


## Paper
The BrSPCD dataset was first introduced in the paper "*Lightweight learning-based sonar point cloud semantic segmentation for underwater bridge inspection*", authored by Zelin Huang, Yanjie Zhu, Wen Xiong*, and Shuaihui Zhang.

<p align="center"><img src="GA.png" alt="file" width="600" height="500">

## BrSPCD

The uploaded dataset includes all 116 fragmented point cloud segments referenced in our publication, along with four complete scene datasets and three binarized datasets derived from other sources. Each compressed package, upon extraction, contains a standardized directory structure with the following three subfolders:
- PointCloud: stores point cloud files in text format, each containing n rows and 3 columns representing 3D coordinates.
- Label: contains label files with n rows and 1 column, where labels “0” and “1” correspond to two semantic classes.
- Visualization: includes .tif images for rapid visual inspection of the data.

<p align="center"><img src="Dataset overview.png" alt="file" width="600" height="500">
