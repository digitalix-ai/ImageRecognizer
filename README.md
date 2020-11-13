# ImageRecognizer
Implementing AI image recognition model

An image recognition app. The app is contained into the file brain.py. It requires pre-installed tensorflow, kernel and imageai libraries. A pre-trained
machine learning model, called InceptionV3, is being implemented in the app. The model is developed by the Google Brain team. The model can be found on
a separate file in the repository, under the name inception_v3_weights_tf_dim_ordering_tf_kernels.h5. There are also 3 additional files with pictures, on
which the model is being tested. But it could be run with other images as well.
The result is being displayed as predictions (words describing the pictures) and probabilities assigned to those predictions as parts from a 100 (percentages).
The number of predictions displayed can be modified and is currently set to 5. 
