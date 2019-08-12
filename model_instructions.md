# ResNet50_tensorflow for image classification
"ResNet50" is the fisrt level title of this markdown, you could use your model name instead, such as "ResNet101", "Mask RCNN", "YOLO3".
```
The usage of markdown title is following:
# This is is an H1
## This is an H2
......
###### This is an H6
```
## Overview
Gives an overview of the model, including but not limited to categories, input data and output format, performance, application, advantanges.

Here is an example of ResNet50:  
This model provides intermediate image feature extraction functionality for image classification. It can also provide top-5 category predictions out of 1000 classes on ImageNet datasets. This network is one of the best models that are both highly efficient and accurate. As a result, it also provides high-quality features for various tasks such as object detection, image segmentation.

```
**General information of ResNet50**

| Key | Value | 
| :-----| ----------------: | #| align left | align right |
| Version | v1.0 |
| By | Xiao Ming | 
| Env | TensorFlow/Py36 | 
| Categories| Computer Vision image classification/object detection/segmentation|
|Type| Model Package|
```

**General information of ResNet50**

| Key | Value | 
| :-----| ----: | 
| Version | v1.0 |
| By | Xiao Ming | 
| Env | TensorFlow/Py36 | 
| Categories| Computer Vision image classification|
|Type| Model Package|


## Highlights
Gives the highlights of the model, including but not limited to the effectiveness, efficiency.  
```
Markdown supports both ordered and unorderd lists.
Unorderd lists are marked with *, +, -.
* This model can extract high-quality image features efficiently.
* This model can predict top-5 predictions on ImageNet.
* This model also provides high-quality features for object detection and image segmentation. 
An orderd list is represented by a number and a '.'.
1. This model can extract high-quality image features efficiently.
2. This model can predict top-5 predictions on ImageNet.
3. This model also provides high-quality features for object detection and image segmentation.
```
* This model can extract high-quality image features efficiently.
* This model can predict top-5 predictions on ImageNet.
* This model also provides high-quality features for object detection and image segmentation. 

1. This model can extract high-quality image features efficiently.
2. This model can predict top-5 predictions on ImageNet.
3. This model also provides high-quality features for object detection and image segmentation. 

## Benchmarking
We benchmark our code thoroughly on two datasets: ImageNet 2012, MS coco, reply on two different scenario: image classification and object detection. Below are the results:

```
| Datasets | Categories|Metrics: values | pretrain_model|
| :----| ---: | -----:|-----:|
| ImageNet 2012|image classification|top-1 err:20.74, top-5 err: 5.25|[TensorFlow_ResNet_imagenet.pb]()|
| MS COCO | object detection(Faster R-CNN)| mAP@.5:48.4||
```

| Datasets | Categories|Metrics: values | pretrain_model|
| :----| ---: | -----:|-----:|
| ImageNet 2012|image classification|top-1 err:20.74, top-5 err: 5.25|[TensorFlow_ResNet_imagenet.pb]()|
| MS COCO | object detection(Faster R-CNN)| mAP@.5:48.4||

## Application/scenario
This model is suitable for visual industry, education industry, the e-commerce industry, which is conducive to greatly improve the efficiency of image feature extration and subsequent task.

## Usage
Gives the usage information of the model, including but not limited to supported content types, API calling.
* Supported content types are image/jpeg, image/png, image/bmp.

* APIs can be used to invoke the model after endpoint creation. [APIs calling](https://support.huaweicloud.com/en-us/ugcall-apig/apig-en-ug-180307057.html). 
```
Call address: https://  
Request method: POST  
**Headers parameter description:** 

|parameter|type|description|
|:----|---:|----:|
|Content-type|STRING|application|
|...|...|...|

Return type: JSON  
**Return parameter description:**

|parameter|description|
|:----|---:|
|acc|acc score|
|...|...|...|
```
Call address: https://  
Request method: POST  
**Headers parameter description:** 

|parameter|type|description|
|:----|---:|----:|
|Content-type|STRING|application|
|...|...|...|

Return type: JSON  
**Return parameter description:**

|parameter|description|
|:----|---:|
|acc|acc score|
|...|...|...|

## Model support
Gives a support for model, could be a github repo Issue link for searching questions and opening new issues. In order to solve the problem effectively, you could leave contact information, such as email address, wechat, phone number.

**Tensorflow ResNet50 Classifier**
Model supported is available from [issue part](https://github.com/keras-team/keras-applications/issues). The users can search for questions and open new issues to ask questions on it. You also contact us by email address contactus@gmail.com or wechat contactus123.

## Acknowledgement
If you owe any attributions or thanks, include them here along with any citations of this projects. 

We would like to thank Lucy and Tony for valuable discussions. This work was partly supported by National Key R&D Program
of China[2019Y12345678](program name or funding name). During our implementing, we referred the [repo](https://github.com/tensorflow/models/blob/master/research/slim/nets/resnet_v1.py) or [paper](https://arxiv.org/abs/1512.03385). 

## Inspiration
Your model will be in front of the world's largest data science community. What questions do you want to see answered?
## Additional Resources

