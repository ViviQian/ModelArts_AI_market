# ResNet50
"ResNet50" is the first level title of this markdown, you could use your model name repalce it.
```
We use markdown code block to write some markdown syntax. The head and tail of a code paragraph are enclosed by '```'. For example:
'```
code paragraph
```'
The usage of markdown title is the following:
# This is is an H1
## This is an H2
......
###### This is an H6
```
## Overview
Here you will give an overview of the model, which could include but not limited to **network structure, data, applications and performance**.

Here is the overview of ResNet50:  
ResNet50 is a 50 layer Residual deep convolutional network. It provides intermediate image feature extraction functionality for image classification. It can also provide top-5 category predictions out of 1000 classes on ImageNet datasets. This network is one of the best models that are both highly efficient and accurate. As a result, it also provides high-quality features for various tasks such as object detection, image segmentation.
```
You could create a table to illustrate the general information of the model. The following syntax is probably used：
1. Create a table:
| Key | Value | 
| :-----| ----: | #| align left | align right |
| key1 | value1 |
| key2 | value2 | 
2. Bold：**example**
3. Create a link: [link name](https://example.com)
4. Quote a picture: ![image name](http://example.com/image.png) 
5. For more details, please refer to https://daringfireball.net/projects/markdown/syntax
```
**General information of ResNet50**

| Key | Value | 
| :-----| ----: | 
| Version | V1.0 |
| By | Xiaoming | 
| Env | TensorFlow-1.8/Python3 | 
| Categories| Computer Vision image classification|
| Data | Image/Photo |
| Network structure | [ResNet50 structure](http://ethereon.github.io/netscope/#/gist/db945b393d40bfa26006) | 


## Highlights
This section needs to provide the highlights of the model. You could describe **effectiveness and efficiency** or other advantages.
```
Markdown supports both ordered and unordered lists.
Unordered lists are marked with *, +, -.
* This is advantage 1.
* This is advantage 2. 
An ordered list is represented by a number and a '.'.
1. This is advantage 1.
2. This is advantage 2. 
```
Here are the highlights of ResNet50:  
* This model can extract high-quality image features efficiently.
* This model can predict top-5 predictions on ImageNet.
* This model also provides high-quality features for object detection and image segmentation. 


## Benchmarking
In this section, you need describe the **performance** of the model on the benchmark datasets. If the datasets are open source, it will be better to attach links.

Here is the benchmarking of ResNet:  
We benchmark our code thoroughly on two datasets: [ImageNet 2012](http://www.image-net.org/), [MS COCO](http://cocodataset.org/#home), respectively reply on two different scenario: image classification and object detection. 
![image](http://res.cloudinary.com/dyd911kmh/image/upload/f_auto,q_auto:best/v1522766480/1_6j34dAOTijqP6HDFnjxPFA_udggex.png)

Below are the results: 

| Datasets | Categories|**Metrics: Values** | 
| :----| ---: | -----:|
| ImageNet 2012 |  image classification          | top-1 err: 24.7%, top-5 err: 7.8% |
| MS COCO       | object detection(Faster R-CNN) | mAP@.5: 48.4  |

## Application
Here you need to outline **What application/scenarios** the model applied to.

For example:
1. research direction：This model is conducive to greatly improve the efficiency of image feature extraction and is suitable for computer vision image classification, object detection, and image segmentation. 
2. practical application: This model is conducive to greatly improve the efficiency of image feature extraction, which can be applied to Face Recognition, Medical Imaging Diagnosis, Driving Assistance and so on. Combining these two points will be easily accepted by users with different needs. 

## Usage
This section will illustrate the usage information of the model. To enhance the user's sense of use,  it is very important to give a detailed description of how to invoke this model. We recommend that it includes at least supported content types and the API calling method.

Here is a usage example:
* Supported content types are image/jpeg, image/png, image/bmp.
* APIs can be used to invoke the model after endpoint creation. [APIs calling](https://support.huaweicloud.com/en-us/ugcall-apig/apig-en-ug-180307057.html). 
    * **Request**
    1. Call address: https://example/modelarts-modelapi1  
    2. Request method: POST  
    3. **Headers parameter description:** 

        |parameter|type|Necessary|value|
        |:----|---:|----:|---:|
        |Content-type|STRING|Yes|application/|
        |...|...|...|...|
    4. Request example:
    ```
    POST https://example/modelarts-modelapi1  
    ...
    ```
    * **Response**
    1. Return type: JSON  
    2. **Return parameter description:**

        |parameter|value|
        |:----|---:|
        |acc|acc score|
        |...|...|...|
    3. Response example:
    ```
    {acc:0.85,...}
    ```
    

## Model support
This section will provide support for the model, which can be a GitHub **Issues** part for searching questions and opening new ones. At the same time, you can leave contact information such as email address, WeChat, and phone number so that users' questions can be answered in a timely manner.

Here is a model support example:   
[Issues part](https://github.com/keras-team/keras-applications/issues) is available. The users can search for questions and open new issues on it. You also can contact us by email address **contactus@gmail.com, wechat contactus123, phone number 12345678912**.

## Acknowledgment
If you owe any attributions or thanks, include them here along with any citations of this projects. 

Here is an acknowledgment example:  
We would like to thank Lucy and Tony for valuable discussions. This work was partly supported by National Key R&D Program
of China (2019Y12345678). During our implementing, we referred the [project](https://github.com/tensorflow/models/blob/master/research/slim/nets/resnet_v1.py) and [paper](https://arxiv.org/abs/1512.03385). 


## Additional Resources
If you have some materials that can help users understand the model or projects that you find interesting, include them here.

