##Implementation of Viola Jones Algorithm for Face Detection

Authored  by : Vishakha Thakurdwarkar

Input data: Used Trainset data for learning 

Details about the code:

External packages used:
1. glob  -  for reading files
2. PIL  -  for operations to be performed with image

Files in the code:
1. FeatureExtraction.py 
Includes reading the input images from folders and extracting the features 
from each image. Selectes the top feature for each image and all the feature data is stored in
FeatureData.csv file.
Also, the location information is stored in FeatureLocation.csv file for reference to get
the location where the best feature is located.

2. Adaboost.py
This file has the function of running the Adaboost classifier to get the strong classifier after number of 
rounds mentioned. The threshold is adjusted by using a trade off between false positive and false negative found 
in this file later. The output is then displayed and has been included in the report.

Getting the environment ready:
The folder where the images are contained has to be included in the same folder as that of the code files.
The csv files would also be saved in the same location.