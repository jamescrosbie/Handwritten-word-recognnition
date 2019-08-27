# Handwritten words recognition

This project takes the handwritten words from [IAM Handwriting Database](http://www.fki.inf.unibe.ch/databases/iam-handwriting-database).  Resizes the images to the same size (by adding padding) and develops a Convolutional Neural Network in Keras to classify the word.

The next stage is to take handwritten sentences and break these into individual words using the [EAST model](link) before feeding these into the keras model.
