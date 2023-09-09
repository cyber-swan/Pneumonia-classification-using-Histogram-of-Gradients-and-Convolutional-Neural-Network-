# Pneumonia-classification-using-Histogram-of-Gradients-and-Convolutional-Neural-Network-
This repositiory contains the Pneumonia classification project. This was done for research purpose, Pneumonia Xray images from Kaggle were utilized for this analysis. 
Feature engineering was the focal point of this research, this was achieved using HOG and classification was done using CNN.
The Images were first normalized to remove any distortion like noise.
The features were extracted using HOG and later correlated using Pearsonr to categorize them into the new labels.
100 Normal and 1500 Pneumonia images were classified {highly class imbalanced}  
The CNN model achieved an accuracy of 87% with low false positive rate. The essence of this research was to assign new labels from the conventional Pneumonia and Normal to a class of Pneumonia which includes Severe, Moderate and Mild, thereby treating it as multiclassification problem not a binary classification.
This research is first of its kind and room for improvement is highly welcomed.
