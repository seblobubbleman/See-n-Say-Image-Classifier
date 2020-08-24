# Fisher Price See'n Say Image Classifier

Data Science project using deep learning for image classification.

## Overview 

For this project I built an image classifier for a staple toy in my childhood the Fisher-Price See 'n Say The Farmer Says. This could be beneficial to any child looking for a new twist on a classic toy. Being in the 21st century most kids have access to an iphone or ipad. The child could take a picture of the animal and an app would provide the Farmer speaking along with the animal sound. This is the underlying model for building something with those capabilities of teaching kids fun facts about the 12 different animals. 

I was able to get the model to predict the sport of the ball with 94% accuracy after minimal tuning. For most of the cases this would meet the need of an end user of the app. To get these results I used transfer learning on a CNN trained on resnet34. This created time efficiencies and solid results.

![](https://github.com/seblobubbleman/See-n-Say-Image-Classifier/blob/master/Matrix%20Image%20Classifier%20.png)

## Notes

This notebook takes you through the process of creating an image classifer for various types of sports balls. It is the notebook that I use in the youtube video linked below. It is based of the 
![fastai lesson two notebook](https://github.com/fastai/course-v3/blob/master/nbs/dl1/lesson2-download.ipynb).

## Config

I recommend using google colab for this project as it makes the gpu configuration far easier. In google colab make sure that you go to runtime -> change runtime type -> gpu.

In colab, running the code should create the folder structure that you need. Drag and drop the photos located 
![here](https://drive.google.com/drive/folders/17-hpsdxjwhQ-BtMxBN4-6Pz2vXakeZ2n) 
into their respective folders. Technically you could skip the the folder creation and just drag and drop the data from the google drive into the colab file destination.

## Data
I used the following chrome extension to download the data from google images. 
![FatKun Batch Download Image](https://chrome.google.com/webstore/detail/fatkun-batch-download-ima/nnjjahlikiabnchcpehcpkdeckfgnohf?hl=en). 
