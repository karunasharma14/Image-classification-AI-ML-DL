# Image-classification-AI-ML-DL

**Abstract :**
Image prediction is an important area of research in machine learning and computer vision and it is an emerging research field that has gained popularity in recent years. The purpose of this paper is to explore the various techniques and approaches that have been used for image prediction using machine learning.

**Introduction** :
The procedure of predicting an image's properties or labels based on its qualities is known as image prediction. Face identification, scene comprehension, and object recognition are just a few of the uses for image prediction.

**Literature Review :**
Due to their capacity to extract hierarchical representations from unprocessed picture input, convolutional neural networks (CNNs) have emerged as the most advanced method for classifying images. Many experiments have been carried out recently to enhance the effectiveness of CNNs for image classification jobs.The AlexNet architecture suggested by Krizhevsky et al. in 2012 was one of the earliest and most significant works in this subject. Rectified linear units (ReLU) were used as activation functions in this architecture, along with overlapping pooling layers and data augmentation methods including random cropping and horizontal flipping. The ImageNet dataset, which consists of thousands of photos across 1,000 different classifications, was processed using the AlexNet architecture at state-of-the-art speed.

**Discussion :**
Our project contributes to the body of research on image classification, particularly using CNNs and ANNs. We utilized the CIFAR-10 dataset, which contains 60,000 32x32 color images in 10 classes, making it a challenging benchmark for image classification models.
Our CNN model achieved an accuracy of 80% on the test set, which is a good result considering the complexity of the dataset. However, there is still room for improvement, and future work could include experimenting with different architectures, hyperparameters, and optimization techniques.
Our ANN model, on the other hand, achieved an accuracy of 50%, which is lower than the CNN model. This is likely due to the fact that ANNs are not as effective at capturing spatial relationships between pixels as CNNs. However, we were able to improve the performance of our ANN model by using dropout and batch normalization techniques.
One limitation of our project is that we only used one dataset for training and evaluation. Future work could include testing our models on other datasets to evaluate their generalization performance. Additionally, we could explore other techniques for improving the performance of our models, such as data augmentation and transfer learning.

In **conclusion**, our project demonstrates the effectiveness of using CNNs for image classification tasks and highlights the potential for improving the performance of ANN models using dropout and batch normalization techniques.


**References :**
Krizhevsky, A., Sutskever, I., & Hinton, G. E. (2012). ImageNet classification with deep convolutional neural networks. Advances in neural information processing systems (pp. 1097-1105).
Simonyan, K., & Zisserman, A. (2014). Very deep convolutional networks for large-scale image recognition. arXiv preprint arXiv:1409.1556.
Deng, J., Dong, W., Socher, R., Li, L. J., Li, K., & Fei-Fei, L. (2009). ImageNet: A large-scale hierarchical image database. In 2009 IEEE conference on computer vision and pattern recognition (pp. 248-255).



