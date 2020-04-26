# Classification of X-Ray/CT scan images of COVID-19 with the help of deep learning-based approach

This repository contains a set of python codes for the classification of various images, such as, HRCT, CT Scan, X-Ray, associated with COVID-19.  In addition, we have added images from different viewpoints (axial view, side by side view) to increase the classification accuracy of the model. We further have incorporated a slight modification on a previous code [1]. The model architecture has been illustrated in the figure below. We have executed the code on Ubuntu version 19.10. The classification needs three python codes as given below.  



  
  
- covid19_ai_diagnoser.py: This file contains the functions for regular Pneumonia tests as well as COVID-19 tests.
- covid19_ai_diagnoser_optimal_model_architecture.py: This file contains function of confusion matrix that is used to measure accuracy of the model. Moreover, the model architecture is also described.
- covid19_ai_diagnoser_ui.py: This python file contributes the user interface to run the model efficiently.

## Data Source:
 - [coronahack-chest-xraydataset](https://www.kaggle.com/praveengovi/coronahack-chest-xraydataset)  
 - [pneumonia-chest-x-ray](https://www.kaggle.com/parthachakraborty/pneumonia-chest-x-ray)  
 - [chest-xray-pneumonia](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)  


## Software Requirement:
- Spyder IDE: 3.0 
- Tensorflow: 1.14.0
- Numpy: 1.18.2 
- Keras: 2.3.1 
- Matplotlib: 3.2.1   
- random: any version
- pillow: 7.0.0
- tkinter: tkintertable-1.3.2
- ipython:5.8.0 

## Hardware Requirement:
- CPU: intel i5 8th gen  8265u
- RAM: 4.00 gb  3200 mhz ddr4 with Radeon 520  Graphics

## Train-test image split

- Train set: normal images: 75, illness-positive images: 5337
- Test set: normal images: 21, illness-positive images: 21

## Result:
- Accuracy: 78.57%
- Precision: 75.0%
- Recall/Sensitivity: 85.71%
- Specificity 71.43%
- F1-score: 80.0

