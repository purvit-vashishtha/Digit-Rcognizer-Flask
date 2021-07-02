# Structure of App

keras - > Tensorflow.js ->(html + css + javascript)->github pages

# Aim:

To make a convolution neural network to recognise handwritten digits by training the model on MNIST dataset available in keras. 

# MNIST DATASET:

The training dataset contain 60000 images and testing contain 10000 images. Each image is 28x28 pixel and grey scale. 

# CNN MODEL OVERVIEW:

⚈ It is a 17 layer model with Conv2D,MaxPooling2D,BatchNormalization,Dense,Flatten and Dropout layer combination. 

⚈ Input layer has 32 neuron and output layer has 10 neurons as 10 different clases exsist. 

⚈ 30 epochs are used. 

⚈ Categorical_loss is loss function and adam is used for optimization. 

⚈ Model gives 99.15% accuracy.

# For Deployment:
Save model using tensorflowjs converters as json file and weight as .h5 file.Use Tensorflow.js to load model and predict in javascript file.
