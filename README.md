# COVID-Prediction-from-Chest-x-ray-Images-with-cnn
In this project, Built and trained a convolutional neural network in Keras with TensorFlow as backend from scratch to predict patients if they were infected with COVID-19 or not using their chest X-ray images. Matplotlib was used for data visualization. Data preprocessing and data augmentation was carried out using tensorflow 2.0 The model used was sequential with a combination of convolutional layers, pooling layers, dropout layers, dense layers with relu activation and output layer with sigmoid activation. The dataset contained the lungs X-ray images of both groups i.e non-covid and covid infected patients. The dataset was obtained from kaggle. Metrics chosen for model evaluation were Training set, test set and validation set accuracy. Adam optimizer with learning rate of 0.001 was choosed for gradient descent The entire project was carried out on the Google Colab environment Results of the model were following:

Training Set Accuracy : 0.96 %

Training Set Loss : 0.1000

Validation Set Accuracy : 0.97 %

Validation Set Loss: 0.0862

Test Set Accuracy : 97.10 %

Test Set Loss : 0.1203

Project Google Colab Link : https://colab.research.google.com/drive/1kqXQ68L8DjfwpSV0vgkCci4VfyUOIwPN?usp=sharing
