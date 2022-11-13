# Crowd-Violence-Detection-using-deep-CNN-model-and-CNN-LSTM-and-explanation-using-XAI

Crowd violence detection using deep learning and the explanation of the learning of the models done by LIME. The CCTV footage is the primary source of violence detection occuring in public. But these videos are of low quality and the violence happening cannot be detected. Therefore, using different CNN models, the videos are classified as violence and non violence and the models trained are explained using the XAI library, LIME. LIME shows the features that help predict the video as violence and non violence.


## Dataset
The dataset is a combination of two datasets from Kaggle. It consists of low quality CCTV footage of violence and non violence videos carried out by individuals in public. There are about 389 violence videos and 280 non violence videos. The shortest video is about 4 to 5 seconds long and the longest video is about 11 minutes long.

https://www.kaggle.com/datasets/shreyj1729/cctv-fights-dataset


https://www.kaggle.com/datasets/toluwaniaremu/smartcity-cctv-violence-detection-dataset-scvd



## Proposed Model

![Slide1](https://user-images.githubusercontent.com/56185553/201461128-0db91ea0-53c9-43b1-9bb4-d356efd7c2aa.JPG)


## CNN models used
1. InceptionNetV3
2. MobileNetV1
3. ResNet50
4. VGG16
5. AlexNet

## Comparison of Accuracy of all the models

| Models   | Training Acc   | Validation Acc   | Testing Acc   |
|----------|----------------|------------------|---------------|
| VGG16    | 49%            | 37%              | 49%           |
| InceptionNetV3    | 97%            | 94%              | 95%           |
| MobileNetV1    | 99%            | 99%              | 99%           |
| ResNet50    | 98%            | 94%              | 95%           |
| AlexNet    | 99%            | 82%              | 77%           |
| CNN+LSTM    | 100%            | 100%              | 100%           |
