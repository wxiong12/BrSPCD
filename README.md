# Bridge Sonar Point Cloud Dataset (BrSPCD) Version_1.0


## Paper
The BrSPCD dataset was first introduced in the paper "*Lightweight learning-based sonar point cloud semantic segmentation for underwater bridge inspection*", authored by Zelin Huang, Yanjie Zhu, Wen Xiong*, and Shuaihui Zhang. It was designed to train and evaluate the performance of semantic segmentation algorithms for underwater bridge sonar point clouds.


<p align="center"><img src="GA.png" alt="file" width="600" height="500">


At the time of BrSPCD’s release, the field lacked publicly available datasets due to the inherent complexities of underwater surveying. This significant gap severely limited the application of deep learning techniques in underwater bridge inspection.
## BrSPCD

The uploaded dataset includes all 116 fragmented point cloud segments referenced in our publication, along with four complete scene datasets and three binarized datasets derived from other sources. Each compressed package, upon extraction, contains a standardized directory structure with the following three subfolders:
- PointCloud: stores point cloud files in text format, each containing n rows and 3 columns representing 3D coordinates.
- Label: contains label files with n rows and 1 column, where labels “0” and “1” correspond to two semantic classes.
- Visualization: includes .tif images for rapid visual inspection of the data.

<p align="center"><img src="Dataset overview.png" alt="file" width="600" height="500">

## Citation
```javascript
console.log(Our article has been accepted by Automation in Construction and will be published online soon. We warmly welcome the research community to follow our work and explore the BrSPCD dataset.");
```
