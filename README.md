 # Object Detection Using SSD MobileNet V2

This repository contains the implementation and training details of an object detection model using SSD MobileNet V2, aimed to efficiently detect objects with a reasonable trade-off between speed and accuracy. 

## Project Overview

The objective of this project is to create a robust object detection system that can accurately detect and locate objects in images. The SSD MobileNet V2 model was chosen due to its efficiency on moderate GPU resources. I used NVIDIA GTX 1650 which is suitable for models which doesnot need high memory or computation speed. The main purpose of this is to create tfrecords and use them for tensorflow pipeline object detection. 

## Model Details

- **Model Architecture**: SSD MobileNet V2
- **Input Image Resolution**: 224x224
- **Number of Classes**: 6
- **Pre-trained Model**: MobileNet V2 trained on COCO dataset

## Dataset

The dataset used for training this model is moderately large, The dataset used is NEU-DET surface defect dataset which has annotations in xml format and images in jpg.
This dataset has 6 surface defects which represent 6 classes. 

## Installation

To set up the project environment, I have uploaded a guide file checkit out.

## Results
The final object detection system is capable of detecting objects with the following accuracy:

Classification Loss: 1.0459441

Localization Loss: 0.48785937


![Detection Resul-1](https://github.com/Charan-Sammeta/object-detection--ssd_mobilenet_v2/blob/main/imageData1.png "Detection Result-1")
![Detection Result-2](https://github.com/Charan-Sammeta/object-detection--ssd_mobilenet_v2/blob/main/imageData2.png "Detection Result-2")
![Detection Result-3](https://github.com/Charan-Sammeta/object-detection--ssd_mobilenet_v2/blob/main/imageData3.png "Detection Result-3")


## References 
[1] SSD Paper: https://arxiv.org/abs/1512.02325

[2] TensorFlow Object Detection API: https://github.com/tensorflow/models/tree/master/research/object_detection

## future development 
I have been working on inputing multiple tfrecord files and also on different model architectures. As soon as i found better results. repo will be updated.