# dataset path:
https://www.kaggle.com/datasets/kaustubhb999/tomatoleaf

# Tomato leaf disease classification using CNN
Used : Convolutional Neural Networks <br>
In this project I used the Tomato Leaf Disease dataset and implemented a CNN model using Keras API. The model achieved high accuracy on the test set.

Step 1: Import Libraries <br>
Step 2: Dataset <br>
Step 3: Data Augmentation <br>
Step 4: Call back setup <br>
Step 5: Model CNN <br>
Step 6: Model History <br>
Step 7: Accuracy and Loss <br>


# Description
We will use the Keras API to implement our CNN model. The model will consist of four convolutional layers, followed by two fully connected layers. Each convolutional layer will have 32 filters and a kernel size of 3×3. We will use ReLU activation functions for all the layers except the output layer, which will have a softmax activation function to generate probability scores for each class. We will use the categorical cross-entropy loss function and the Adam optimizer for training the model.
