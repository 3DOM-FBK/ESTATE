## ESTATE - A LARGE DATASET OF UNDER-REPRESENTED URBAN OBJECTS FOR 3D POINT CLOUD CLASSIFICATION

We offer to the community the ESTATE dataset which combines available datasets creating from various sensors, densities, regions and object types. 

## Why ESTATE?
- to better handle and segment generally under-represented urban objects in available datasets/benchmarks which can hardly be segmented with state-of-the-art neural networks;
- to support generalization issues across datasets using current deep learning approaches due to the heterogeneity of sensors, data and locations.

<center>Some representative datasets for object classification in point clouds:
<img src="https://github.com/3DOM-FBK/ESTATE/blob/master/sota.png">
</center>

ESTATE includes 13 classes featuring intensity and/or colour attributes, extracted and merged from 11 MLS / ALS / UAV-Photogrammetry available datasets:
- Light Pole
- Traffic Light
- Pole
- Electrical Pole
- Traffic Sign
- Pylon
- Cable
- Garbage Box
- Car
- Truck
- Bus
- Chimney
- Ventilation

<center>
Selected datasets and extracted objects (classes) in ESTATE:
<img src="https://raw.githubusercontent.com/3DOM-FBK/ESTATE/master/estate_classes.png">
</center>

<center>
Some objects included in the ESTATE dataset:
<img src="https://raw.githubusercontent.com/3DOM-FBK/ESTATE/master/estate.png">
</center>

Our experiments with ESTATE demonstrated that the dataset improves the classification performance of deep learning techniques and could be a game-changer to advance in the 3D classification of urban objects.
The ESTATE dataset contains data in three different configurations: 
- XYZ 
- XYZ + RGB
- XYZ + intensity
Two different training and testing approaches were applied:
- Single-Train Single-Test - **STST**: randomly selected 70% of the objects in each dataset as training and 30% as test and perform training and testing for each dataset;
- All-Train All-Test - **ATAT**): all train and test sets of STST are merged to examine the classification performance in general.
  
So far only the training sets are shared, on the other hand, the test sets of the dataset will be shared after the review process of our journal paper is completed.

## Download of the training sets
|  Dataset | link |
|---|---|
|  STST | <a href="https://drive.google.com/drive/folders/12fJYh1dJ2Z0_XM9chfdBrpATVPL_z4XB?usp=drive_link">download</a>|
|  ATAT | <a href="https://drive.google.com/drive/folders/18w5ilOIlrd2NjDAEz68RYNIDxLBBqNEs?usp=drive_link">download</a>|


## Credits and reference
The ESTATE dataset is publicly available for research purposes. If you use this dataset for your research, please cite the repository and following publication: 
- O. C. Bayrak, M. Zhenyu, E. M. Farella, F. Remondino, and M. Uzar, 2024: <a href="https://isprs-archives.copernicus.org/articles/XLVIII-2-2024/25/2024/" target=page>ESTATE: a large dataset of under-represented urban objects for 3D point cloud classification</a>. The International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences, vol. XLVIII-2-2024, pp. 25-32


## License
The data provided here is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.



