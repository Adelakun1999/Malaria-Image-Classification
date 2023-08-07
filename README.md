# Malaria-Image-Classification

Malaria Image Classification using Convolutional Neural Networks (CNN)

This project aims to classify malaria-infected and uninfected cells in microscope images using Convolutional Neural Networks (CNNs). The dataset consists of thousands of cell images that are labeled as either infected or uninfected. The CNN model will be trained on this dataset to learn the features that distinguish between the two classes and make accurate predictions on unseen data.

<h2>Dataset</h2>

The dataset used in this project contains two classes:
<ul>
  <li>Infected: Microscope images of cells infected with malaria parasites.</li>
  <li>Uninfected: Microscope images of healthy cells without malaria parasites</li>
</ul>

<h2>Model Architecture</h2>

<p>The CNN model used for malaria image classification consists of multiple convolutional layers, followed by max-pooling layers to extract features from the images. The output is then flattened and passed through fully connected layers for classification. The model will be trained on the training data and evaluated on the test data to measure its accuracy.</p>

<h3>Result</h3>

The trained CNN model will provide predictions on new and unseen malaria cell images. The classification accuracy and other evaluation metrics will be provided to assess the model's performance.

<h2>Conclusion</h2>

This project demonstrates the use of Convolutional Neural Networks for malaria image classification. It serves as a starting point for further improvements and experimentation with different network architectures, data augmentation techniques, and hyperparameter tuning to achieve better accuracy and generalization.

