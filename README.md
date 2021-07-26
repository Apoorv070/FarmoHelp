## CROP DISEASE DETECTOR 

## Problem statement :
Crop diseases are a huge danger to food security, but due to a lack of infrastructure in many regions of the world, timely detection is challenging.

## Motivation:
It was during Lockdown when I was in my hometown. I used to visit the farm every day just for fun . There I used to talk with a lot of farmers to get some insights about their life and about these crops where I came to know that almost 1000 of plants die due to some diseases in every cycle.AS those days i was also doing my summer training in machine learning so i thought can we use artificial intelligence to resolve this thing.I researched and found a public data set for these crop images and also lot of previous works conducted in this field.

## Solution :
A Flask web app on which farmers can upload the photo of the leaf form their mobile phone and check whether the leaf is safe or infected and if infected what solutions and remedies farmers can do for the same.

## Dataset :

Dataset : https://www.kaggle.com/janmejaybhoi/cotton-disease-dataset
## Steps :
1) Data Augmentation / Data Generator 
2) Tried different Models:
  ## Approach:
  I tried various image classification techniques.
  ### 1.CNN Model:
  ![img](https://github.com/Apoorv070/Crop_Disease_Detector/blob/main/download.png)
  ### 2.Transfer Learning VGG 16 
  ![img](https://github.com/Apoorv070/Crop_Disease_Detector/blob/main/download2.png)
  ### 3.Transfer Learning Inception V3 using Keras
  ![img](https://github.com/Apoorv070/Crop_Disease_Detector/blob/main/img3.png)
  ###


 4.Transfer Learning using Resnet 50:
  ![img](https://github.com/Apoorv070/Crop_Disease_Detector/blob/main/image4.png)
  
## Results obtained:
![img](https://github.com/Apoorv070/Crop_Disease_Detector/blob/main/result1.PNG)
![img](https://github.com/Apoorv070/Crop_Disease_Detector/blob/main/result2.PNG)
## Demo video of the prototype

Link : https://www.youtube.com/watch?v=774T8iaN8GA


https://user-images.githubusercontent.com/47479228/126924827-25f35f51-b280-4cea-b4d9-0a04fa7371ab.mp4
