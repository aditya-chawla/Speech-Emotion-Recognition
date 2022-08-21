# Speech-Emotion-Recognition
## Aim: To build a model to recognize emotion from speech using the librosa and sklearn libraries and the RAVDESS dataset.
## About: 
### Speech Emotion Recognition
* Speech Emotion Recognition, abbreviated as SER, is the act of attempting to recognize human emotion and affective states from speech.
### Libraries used 
* librosa is a Python library for analyzing audio and music.
* SoundFile is an audio library for reading and writing sound files.
### Dataset Used
* The RAVDESS dataset is the Ryerson Audio-Visual Database of Emotional Speech and Song dataset, and is free to download.
### Classification Model
* Multi-layer Perceptron classifier- This model optimizes the log-loss function using LBFGS or stochastic gradient descent.

## Procedure:
* Load the data, extract features from it, then split the dataset into training and testing sets. 
* Define a function to extract the features from a sound file.
* Build a MLPClassifier model which will be able to recognize emotion from sound files. 
* Initialize the MLPClassifier and train the model.
* Calculate the accuracy of our model.
##  Conclusion:
Successfully recognized emotions from speech using an MLPClassifier for this and made use of the soundfile library to read the sound file, and the librosa library to extract features from it. The model delivered an accuracy of 72.9%
