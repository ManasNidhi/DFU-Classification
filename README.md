# DFU-Classification
# Diabetic Foot Ulcer Classification using Deep Learning
Experimented with five different CNN architectures (InceptionV3, ResNet50, DenseNet121, MobileNet, and VGG16) to classify images of Diabetic Foot Ulcers. These models were trained using transfer learning, starting with pre-trained weights from ImageNet and fine-tuning them on the target dataset.

The dataset used in the study consisted of 1051 images, which underwent preprocessing and augmentation before training the models. The models were trained, validated, and tested on separate sets of data. We have used evaluation metrics such as accuracy, F1 score, and ROC-AUC score to compare the performance of the models.

Among the architectures tested, the VGG16 model achieved the highest accuracy and F1 score. On the testing dataset, the VGG16 model achieved an accuracy of 96.68% and an F1 score of 0.96.

Flowchart:
![image](https://github.com/user-attachments/assets/9727e13e-8c1a-45b7-b326-b35d29f5d288)


Resources :
  Read the associate research paper [here](https://link.springer.com/chapter/10.1007/978-981-99-1983-3_35) for further details
