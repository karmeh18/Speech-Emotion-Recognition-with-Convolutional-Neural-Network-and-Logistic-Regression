# Speech-Emotion-Recognition-with-Convolutional-Neural-Network-and-Logistic-Regression

Speech Emotion Recognition (SER) is the process of identifying the emotional state of a speaker from their speech. One way to achieve this is by using Convolutional Neural Networks (CNN) in conjunction with Logistic Regression (Logistic Regression). This approach involves extracting the Mel-frequency cepstral coefficients (MFCCs) from the audio signal using the librosa library, which are then converted into a spectrogram.

The steps to implement this approach are:

1. Load the audio dataset and create a list of labels for each audio file.
2. Extract the MFCC features for each audio file using the librosa library.
3. Convert the MFCC features into a spectrogram for training the CNN model.
4. Train the CNN model on the spectrogram data to classify the audio files into one of the seven different emotion classes.
5. Use the output of the CNN as features to train a Logistic Regression model to predict the emotional state of the speaker.
In the first step, we load the audio dataset and create a list of labels for each audio file. The labels are used to classify the audio files into one of the seven different emotion classes, which are anger, disgust, fear, happiness, neutral, sadness, and surprise.

In the second step, we use the librosa library to extract the MFCC features for each audio file. The MFCC features capture the spectral characteristics of the audio signal and are commonly used in speech analysis tasks.

In the third step, we convert the MFCC features into a spectrogram for training the CNN model. The spectrogram is a visual representation of the spectrum of frequencies of the audio signal as it varies with time.

In the fourth step, we train the CNN model on the spectrogram data to classify the audio files into one of the seven different emotion classes. The CNN model is trained using the spectrogram data and the corresponding labels.

In the fifth and final step, we use the output of the CNN as features to train a Logistic Regression model to predict the emotional state of the speaker. The output of the CNN is a set of features that represent the audio signal, which can be used to predict the emotional state of the speaker using a Logistic Regression model.
