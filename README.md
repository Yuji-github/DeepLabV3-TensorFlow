# DeepLabV3+ with TensorFlow

## Motivation

One of the novel AI models is computer vision. There are many different types of computer vision models, such as mask-rcnn, u-net, and so on. This project aims to introduce the state-of-the-art computer vision model, [DeepLabV3+](https://arxiv.org/abs/1802.02611v3). This model is a semantic segmentation architecture, and atrous convolution was introduced in DeepLab as a tool to adjust and control the effective field-of-view of the convolution.
<img src="./src/dilated.gif" alt="aspp" title="aspp"><br>
The above picture shows how the atrous convolution works. In comparison with regular CNN, the method skips pixels, and this can capture more information about pictures while they are in encoding. 

The below picture shows the entire model architecture, and it shows that the atrous convolution method used in Atrous Spatial Pyramid Pooling (ASPP).
<img src="./src/aspp.png" alt="aspp" title="aspp"><br>



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
