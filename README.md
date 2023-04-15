# Problem Statement:

The objective of this project is to implement a Convolutional Neural Network (CNN) in PyTorch to perform single-object segmentation, specifically, to segment the fetal head in ultrasound images. The dataset used for this project can be downloaded from the provided link, which contains training_set and test_set folders. The training_set folder consists of 1998 png files, including 999 images and 999 annotations. The test_set folder contains 335 png images with no annotation files.

The project tasks are:

1. Create a custom dataset by splitting the training_set into 799 images for training and 200 images for validation.
2. Develop a custom encoder-decoder model for fetal head segmentation, experiment with different combinations like any number of layers in the encoder-decoder, any activation function, any optimizer, any learning rate, etc. and calculate the Dice score as the evaluation metric.
3. Compare the Dice score of the custom encoder-decoder model with the plain UNet model.
4. Plot the training and validation losses with the number of epochs and also plot the train-validation metrics plot.
5. Deploy the best model on the test_set and display the images and predicted output of the model on test_set.
