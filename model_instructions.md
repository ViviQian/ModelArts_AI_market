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
Gives an overview of the model, including but not limited to categories, input data and output format, application/scenario, advantages.

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
| Categories| Computer Vision image classification|
|Type| Model Package|



```
**General information of ResNet50**

| Datasets | Categories|Metrics: values | pretrain_model|
| :----| ---: | -----:|-----:|
| ImageNet 2012|image classification|top-1 err:20.74, top-5 err: 5.25|[TensorFlow_ResNet_imagenet.pb]()|
| MS COCO | object detection(Faster R-CNN)| mAP@.5:48.4||
```
**Performance of ResNet50 on various scenario**

| Datasets | Categories|Metrics: values | pretrain_model|
| :----| ---: | -----:|-----:|
| ImageNet 2012|image classification|top-1 err:20.74, top-5 err: 5.25|[TensorFlow_ResNet_imagenet.pb]()|
| MS COCO | object detection(Faster R-CNN)| mAP@.5:48.4||


## Highlights
Gives the highlights of the model, including but not limited to the effectiveness, efficiency.  
```
Markdown supports both ordered and unorderd lists.
Unorderd lists are marked with *, +, -.
* This model can extract high-quality image features efficiently.
* This model can predict top-5 predictions on ImageNet.
* The state-of-the-art performance with accuracy of 79.15 vs. 75.3 in the original paper. 
An orderd list is represented by a number and a '.'.
1. This model can extract high-quality image features efficiently.
2. This model can predict top-5 predictions on ImageNet.
3. The state-of-the-art performance with accuracy of 79.15 vs. 75.3 in the original paper. 
```
* This model can extract high-quality image features efficiently.
* This model can predict top-5 predictions on ImageNet.
* The state-of-the-art performance with accuracy of 79.15 vs. 75.3 in the original paper.

1. This model can extract high-quality image features efficiently.
2. This model can predict top-5 predictions on ImageNet.
3. The state-of-the-art performance with accuracy of 79.15 vs. 75.3 in the original paper.

## Usage
Gives the usage information of the model, including but not limited to supported content types, API calling method.
* Supported content types are image/jpeg, image/png, image/bmp.

* Model APIs can be used to invoke the model after endpoint creation, e.g., using aws-cli:
```
aws sagemaker-runtime invoke-endpoint --endpoint-name your_endpoint_name --body fileb://img.jpg --accept image/jpeg --custom-attributes '{"feature": "flat"}' feat.out
```
## Model support
Gives a support for model, could be a github repo Issue link for searching questions and opening new issues.


**Tensorflow ResNet50 Classifier**
Model supported is available from [link](). Search for questions and open new issues to ask questions.

## Acknowledgement
If you owe any attributions or thanks, include them here along with any citations of this projects. 

We would like to thank Lucy and Tony for valuable discussions. This work was partly supported by (program name or funding name). During our implementing, we referred the repo [repo link]() or paper[paperlink](). 

## Inspiration
Your model will be in front of the world's largest data science community. What questions do you want to see answered?
## Additional Resources

