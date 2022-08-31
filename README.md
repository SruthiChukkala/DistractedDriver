# Distracted Driver Detection
### Team members

- Mouni Preetham Malyala EE18B019
- B Midhun Varman EE18B113
- Dola Akhila Datta EE18B131

### Description

Developed a Machine Learning Model (We used the state-of-the-art model - CNN ) to classify a driver image into
10 pre-defined categories, where the first category is Safe driving and other categories involve some specific kind of
common distraction activities like texting, talking on phone etc. <br />
We used Transfer learning to greatly improve training time and accuracy using pre-trained models such as VGG-16,
ResNet-50 and MobileNET to achieve an accuracy of 92.68% and a log-loss of 0.23462.  <br />

Submission Details: Private score is 0.23462 and the expected rank is 115. 
Submission’s rank would be 115 (calculated
based on my private score given by Kaggle), if we would have submitted our predictions during
the active phase of this competition.  <br />

### Dataset
Dataset is can be downloaded from [kaggle](https://www.kaggle.com/c/state-farm-distracted-driver-detection)
```
! kaggle competitions download -c state-farm-distracted-driver-detection
```
Further information on downloading from kaggle can be obtained from [here](https://www.kaggle.com/docs/api)

### Goal of the Project

To implement different classification techniques to detect if a driver is paying attention to the road or is involved in some distraction activities and to classify the distraction activities. (texting, talking, reaching around, etc.) <br />
Implementing the below 3 classification models and calculating the accuracy for these models: - <br />
Linear SVM  <br />
Naive Bayes  <br />
Convolutional Neural Networks <br />


### References

- DataTurks: Data Annotations Made Super Easy. “[Understanding SVMs’: For Image Classification](https://medium.com/@dataturks/understanding-svms-for-image-classification-cf4f01232700).” medium.
- Satya Naren Pachigolla. “[Distracted Driver Detection using Deep Learning.](https://towardsdatascience.com/distracted-driver-detection-using-deep-learning-e893715e02a4)” towardsdatascience.
