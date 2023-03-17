# Face-Mask-Detection
We conducted a study on face mask detection. The dataset was sourced from "https://www.kaggle.com/ashishjangra27/face-mask-12k-images-dataset". However, due to limited resources, we trimmed the data to meet our research requirements.

# Problem Description
Face mask detection research has gained attention in the community of computer vision recently due to the FACTS (Face coverings, Avoid Crowding, Clean hands, Two-meter Distance, Self-Isolating) of COVID-19. It has also initiated in development of models in automatic detection. It is a classification as well as a detection problem, which needs to locate the face first and then identify if there was a mask or without the mask. Locating the face has been extensively studied in computer vision on the other hand prediction of face masks has recently gained interest due to the situation of COVID-19 (Batagelj. B, et al., 2021).

# Earlier Findings
To make a good model we need a large volume of datasets in training the model and test it with the data so that it can perform well in real-time applications. This promotes different types of deep learning algorithms which can straightforward detect face and mask forgiven any user data. There are many variations in face mask detector models like easy haar features with boosted cascade, and classification based on boosting (Nagrath. P et al., 2021).

The researcher (Zhang, Zhang, Li, and Qiao, 2016) had created a Deformable Part Model-based classification-based model, the model was built using 30,000 images to train and test the model. The model gave an exceptional accuracy of 97.14%. These types of models give efficient precisions but with high computational cost in real-world development.

# Aims and Objectives
Our team proposed the following aims and objectives:

Performance of mask detectors for different skin tone.
Check different types of masks like Surgical, Reusable, N95 for the same person.
Also to check with varieties of backgrounds, clothes, angles and with/without glasses.
Evaluation of complexity and accuracy of a model.
From the earlier findings, we are planning to achieve light weight face mask detection model and with less computational cost model which can be implemented in the real-world applications.

# Data Collection
We have taken dataset to build the model from https://www.kaggle.com/omkargurav/face-mask-dataset. Which includes images from different skin tone, age group and ethnicities. There are a wide range of classes like face shield mask, with hats and other special categories. 6461 images for the training data and 1092 images for the test data.

To test the model in real world images, we have used our own team members customised dataset around 50 images. These images contain with varieties of backgrounds, clothes, angles, with/without glasses and different types of masks.

# Conclusion
We conclude from all the above models ResNet18 pretrained gave high accuracy range of 90 - 95%. We have validated the model with our own personal images of same person with different angles, different mask (Surgical, N95, Reusable), different clothes, different background, with glasses on, with hoodie along with its cap.

We have achieved all the proposed aims and objectives along with the accuracy and complexity of a model. We have also developed a model with less data and less computational cost which is comparable to models that requires high computational cost. However, there are some cases like person with thick or long beard and when there is noise in the image in these situations our model failed to detect correctly.

In future, there is a possibility of the model to predict mask/no mask on the person with thick or long beard and in noisy conditions. It can be implemented in the real-time video camera as well.

# References

Budka, M. (2021). Computer Vision Lecture Content.
Batagelj, B.; Peer, P.; Štruc, V.; Dobrišek, S, (2021). How to Correctly Detect Face-Masks for COVID-19 from Visual Information?. Appl. Sci. 2021, 11, 2070. https://doi.org/10.3390/app11052070.
Jiang.M, Fan.X, and Yan.H, (2020). RETINAFACEMASK: A FACE MASK DETECTOR. Innovation and Technology Commission, and City University of Hong Kong (Project 9410460).
Face Mask Detection Dataset: https://www.kaggle.com/omkargurav/face-mask-dataset.
Sanjaya, S. A. and Rakhmawan, S. A. (2020) ‘Face Mask Detection Using MobileNetV2 in the Era of COVID-19 Pandemic’, 2020 International Conference on Data Analytics for Business and Industry: Way Towards a Sustainable Economy, ICDABI 2020. doi: 10.1109/ICDABI51230.2020.9325631.
Preeti Nagrath, Rachna Jain, Agam Madan, Rohan Arora, Piyush Kataria, Jude Hemanth, (2021). “SSDMNV2: A real time DNN-based face mask detection system using single shot multibox detector and MobileNetV2”, Sustainable Cities and Society, Volume 71, August 2021, Pages 102964.
K. Zhang, Z. Zhang, Z. Li, Y. Qiao, (2016). Joint face detection and alignment using multi-task cascaded convolutional networks IEEE Signal Processing Letters, 23 (10) (2016), pp. 1499-1503.
