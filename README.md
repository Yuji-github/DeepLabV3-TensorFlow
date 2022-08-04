# DeepLabV3+ with TensorFlow

## Motivation

One of the novel AI models is computer vision. There are many different types of computer vision models, such as mask-rcnn, u-net, and so on. This project aims to introduce the state-of-the-art computer vision model, [DeepLabV3+](https://arxiv.org/abs/1802.02611v3). This model uses convolution, DeepLabV3 uses an improved ASPP module by including batch normalization and image-level features. It gets rid of CRF (Conditional Random Field) as used in V1 and V2.



## 1.Requiremnents

Python ==> 3.8<br>
TensorFlow ==> version 2+<br>

Assume DataFolder: <br>
DeepLab <br>
   ----> Train_Images (for training) <br>
   ----> Train_Masks (for training) <br>
   ----> Val_Images (for validation) <br>
   ----> Val_Masks (for validation) <br>
   ----> Test_Images (for testing) <br>
   ----> Test_Masks (for testing) <br>
   ----> Output (for Saving model) <br>

## 2.Datsets
Image Resources: [Link](https://www.kaggle.com/tapakah68/segmentation-full-body-mads-dataset) 


## 3.Demo

## 4.Results
