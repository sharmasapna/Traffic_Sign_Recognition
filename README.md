## Traffic Sign Recognition
### A project done by <br> Dewanshi Deswal, Sapna Sharma and Sarang Pandey <br> as a Capstone project for DS5500, Northeastern University,Boston.



<img src="https://github.com/sharmasapna/Traffic_Sign_Recognition/blob/main/data/German-traffic-sign.png" width="300" height="300">

## Summary

In today’s world, as the number of vehicles is increasing, so are the problems associated with them. One of the many problems is the high number of road mishaps that are caused resulting in fatal accidents. One of the main reasons for this is that people often don’t recognize or follow traffic sign boards set up by the government to ensure the safety of everyone around. So we have decided to make a traffic sign recognizer which can inform the driver of the vehicle about the traffic sign coming ahead and to follow it. This can substantially reduce the number of road accidents and save lives.

Traffic signs are an essential part of our day-to-day lives. They contain critical information that ensures the safety of all the people around us. There are several different types of traffic signs like speed limits, no entry, traffic signals, turn left or right, children crossing, no passing of heavy vehicles, etc. Traffic signs classification is the process of identifying which class a traffic sign belongs to. It has a very major role to play in self-driving cars, which is the future of the automobile industry.

## Data Description

The GTSRB dataset (German Traffic Sign Recognition Benchmark) is provided by the Institut für Neuroinformatik group. It was published for a competition held in 2011. Images are spread across 43 different types of traffic signs and contain a total of 39,209 train examples and 12,630 test ones. The features available along with the images are as follows:

Width: Width of the image in pixels
Height: Height of the image in pixels
Roi.X1: Upper left X-coordinate of the bounding box.
Roi.Y1: Upper left Y-coordinate of the bounding box.
Roi.X2: Lower right X-coordinate of the bounding box.
Roi.Y2: Lower right Y-coordinate of the bounding box.
ClassId: Class label of the image. It is an Integer between 0 and 43.
Path: Path where the image is present in the Train folder. 
 
 
## Proposed Plan

We plan to build models based on deep neural networks to classify the traffic signs present in the image into different categories. First, we intend to update the image sizes and reshape each image to a consistent format. Next, we will divide the training data into train and validation sets (25% of images for validation). We will try out multiple deep learning models and evaluate them based on factors like F1-score, Precision, Recall etc. We will also ensure that there is no overfitting in the model by assessing model loss. If time permits, we also intend to create a GUI that code predicts the signs in real time. 

## Preliminary Results

The classes are clearly not uniformly distributed, as can be seen in Figure 1. There are certain signs that appear more often than others. Less numbers of images can potentially undermine the training process.
<img src="https://github.com/sharmasapna/Traffic_Sign_Recognition/blob/main/data/train_sample_distribution.png">

Figure 1: Train data samples in each class


The images come in varied dimensions. Majority of the images fall between 32 to 64 pixels. We will have to tackle this by making the height and width constant for all images. 
<img src="https://github.com/sharmasapna/Traffic_Sign_Recognition/blob/main/data/train_size_distribution.png">
Figure 2 shows the distribution of various image dimensions available in the dataset



    
    

<!---

<img src="https://github.com/sharmasapna/BlueBike_Traffic_Forecasting/blob/main/data/EDA_Results.png">

<img src="https://github.com/sharmasapna/BlueBike_Traffic_Forecasting/blob/main/data/Hourly_Weekday_Heatmap.png" width="400" height="200"><img src="https://github.com/sharmasapna/BlueBike_Traffic_Forecasting/blob/main/data/bb_from_to stations_heatmap.png" width="200" height="200">

<!---
