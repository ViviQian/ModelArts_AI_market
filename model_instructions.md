# ResNet50
"ResNet50" is the fisrt level title of this markdown, you could use your model name instead, such as "ResNet101", "Mask RCNN", "YOLO3".
```
The usage of markdown title is following:
# This is is an H1
## This is an H2
......
###### This is an H6
```
## Overview
Here you will give an overview of the model, which can include but not limited to categories, data, performance, application and advantanges.

Here is an example of ResNet50:  
ResNet50 is a 50 layer Residual deep convolutional network. It provides intermediate image feature extraction functionality for image classification. It can also provide top-5 category predictions out of 1000 classes on ImageNet datasets. This network is one of the best models that are both highly efficient and accurate. As a result, it also provides high-quality features for various tasks such as object detection, image segmentation.
```
You could create a table to illustrate the general information of the model. The following syntax is probably used：
1. Bold：**example**
2. Create a link: [example](https://example.com)
3. Quote a picture: ![image name](http://example.com/image.png) 
4. Create a table:
| Key | Value | 
| :-----| ----: | #| align left | align right |
| key1 | value1 |
| key2 | value2 | 
5. For more details, please refer to the [blog](https://daringfireball.net/projects/markdown/syntax)
```
**General information of ResNet50**

| Key | Value | 
| :-----| ----: | 
| Version | V1.0 |
| By | Xiao Ming | 
| Env | TensorFlow-1.8/Python3 | 
| Categories| Computer Vision image classification/object detection/segmentation|
| Data | Image/Photo |
| Network structure | [ResNet50 structure](http://ethereon.github.io/netscope/#/gist/db945b393d40bfa26006) | 


## Highlights
This section needs to provide the Highlight of this model. You could describe the model's effectiveness and efficiency, or any other advantages that can appeal to the user.
```
Markdown supports both ordered and unorderd lists.
Unorderd lists are marked with *, +, -.
* This is advantage 1.
* This is advantage 2. 
An orderd list is represented by a number and a '.'.
1. This is advantage 1.
2. This is advantage 2. 
```
Here is the Highlights of ResNet50:
* This model can extract high-quality image features efficiently.
* This model can predict top-5 predictions on ImageNet.
* This model also provides high-quality features for object detection and image segmentation. 


## Benchmarking
In this section, you will describe the performance of the model on the benchmark datasets. If the datasets are open source, it will be better to attach links.

Here is a example of ResNet:
We benchmark our code thoroughly on two datasets: [ImageNet 2012](http://www.image-net.org/), [MS COCO](http://cocodataset.org/#home), respectively reply on two different scenario: image classification and object detection. 
![image](http://res.cloudinary.com/dyd911kmh/image/upload/f_auto,q_auto:best/v1522766480/1_6j34dAOTijqP6HDFnjxPFA_udggex.png)

Below are the results: 

| Datasets | Categories|Metrics: Value | Pretrained_model|
| :----| ---: | -----:|-----:|
| ImageNet 2012|image classification|top-1 err: 20.74, top-5 err: 5.25|[resnet50_imagenet](http://download.tensorflow.org/models/resnet_v1_50_2016_08_28.tar.gz)|
| MS COCO | object detection(Faster R-CNN)| mAP@.5: 48.4|[faster rcnn_resnet50_coco](http://download.tensorflow.org/models/object_detection/faster_rcnn_resnet50_coco_2018_01_28.tar.gz)|

## Application
What scenairos does the model apply to?  

It may be like "This model is suitable for visual industry, which is conducive to greatly improve the efficiency of image feature extration and subsequent task such as image classification, object detection and image segementation", or includes practical application scenario like "This model is conducive to greatly improve the efficiency of image feature extration, which can be applied to face recognition, Medical imaging diagnosis, Driving assistance and so on". Obviously, combining these two points will be easily accepted by users with different needs. 

## Usage
This section will illustrate the usage information of the model. In order to enhance the user's sense of use,  it is very important to give a detailed description of how to invoke this model. We recommend that it includes at least supported content types and the API calling method.

Here is a exampel:
* Supported content types are image/jpeg, image/png, image/bmp.
* APIs can be used to invoke the model after endpoint creation. [APIs calling](https://support.huaweicloud.com/en-us/ugcall-apig/apig-en-ug-180307057.html). 

Call address: https://example/modelarts-modelapi1  
Request method: POST  
**Headers parameter description:** 

|parameter|type|Necessary|description|
|:----|---:|----:|---:|
|Content-type|STRING|Yes|application/|
|...|...|...|...|

Return type: JSON  
**Return parameter description:**

|parameter|description|
|:----|---:|
|acc|acc score|
|...|...|...|

## Model support
This section will provide support for the model, which can be a github **Issues** part for searching questions and opening new ones. At the same time, you can leave contact information such as email address, WeChat, and phone number so that users' questions can be answered in a timely manner.

Model support could be like this: 
[Issue part](https://github.com/keras-team/keras-applications/issues) is available. The users can search for questions and open new issues on it. You also can contact us by email address contactus@gmail.com, wechat contactus123, phone number 12345678912.

## Acknowledgement
If you owe any attributions or thanks, include them here along with any citations of this projects. 

Here is an example:
We would like to thank Lucy and Tony for valuable discussions. This work was partly supported by National Key R&D Program
of China[2019Y12345678](program name or funding name). During our implementing, we referred the [project](https://github.com/tensorflow/models/blob/master/research/slim/nets/resnet_v1.py) and [paper](https://arxiv.org/abs/1512.03385). 

## Inspiration
Your model will be in front of huaweichould users. What questions do you want to see answered?
## Additional Resources
If you has some materials that can help users understand the model or some projects that you find interesting, include them here.

