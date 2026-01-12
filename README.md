# Neural-Networks

Machine learning project using Neural Networks to showcase advanced data modelling for improved performance and accuracy

**Title:** Chest X-Ray Image Classification for Pneumonia Detection using Convolutional Neural Network

**Goal:** Create an image classification model using Convolutional Neural Networks to detect Pneumonia in Chest X-rays.

**Dataset:** https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia

**Methods:**
1. Load and pre-process image data
2. Build convolutional neural network - using Keras, Tensorflow
3. Fine tune hyperparameters and evaluate model performance in terms of runtime/speed and validation accuracy.
4. Evaluation metrics and ROC Curve

**Final Model Architecture:**
A convolutional neural network consisting of three sequential convolutional blocks with 32, 64, and 128 filters, each using ReLU activation, followed by batch normalization and max pooling to progressively extract and condense spatial features. The learned feature maps are flattened and passed to a fully connected dense layer with 128 neurons, where dropout is applied to reduce overfitting, and a final sigmoid-activated output layer produces the probability of pneumonia.

**Final Model Metrics**
- Training Speed:  17min. 45 secs
- Accuracy:        0.9463
- Loss:            0.1770
- Val_Accuracy:    0.9617
- Val_Loss:        0.1175
- Accuracy:        0.7917
- Precision:       0.7559
- Recall :         0.9846
- F1-score:        0.8552
- ROC AUC Score:   0.9349
