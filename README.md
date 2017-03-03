# ML-LetterPredictor-Android

A simple application that shows how to connect and use a TensorFlow model in an Android application.

The app is able of recognising hand-written letters the user inputs using his/her finger.

## The Model

The app relies in a model generated by TensorFlow. The machine learning project is part of the Udacity course on Deep Learning.

It is build as a deep neural network with three hidden layers trained with batches of images in B&W

### Limitations

The model can only predict capital letters from A to H. More soon ;)

The input must be transformed into a B&W image with a single channel. This is done by using OpenCV

## Links

Machine learning project: https://github.com/mccorby/ML-DeepLearning-Course

Course: https://www.udacity.com/course/deep-learning--ud730