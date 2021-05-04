# Speech-Emotion-Recognition
A project to o build a speech emotion detection classifier.
Datasets used in this project are from kaggle - 
  Crowd-sourced Emotional Mutimodal Actors Dataset (Crema-D)
  Ryerson Audio-Visual Database of Emotional Speech and Song (Ravdess)
  Surrey Audio-Visual Expressed Emotion (Savee)
  Toronto emotional speech set (Tess)
Created a dataframe storing all emotions of the data in dataframe with their paths to to extract features.
Data Visualisation and Exploration - counted each emotion in our dataset and plotted waveplots and spectograms for audio signals
Data Augmentation - To generate syntactic data for audio, we can apply noise injection, shifting time, changing pitch and speed.
Feature Extraction - extracting 5 features:
  Zero Crossing Rate
  Chroma_stft
  MFCC
  RMS(root mean square) value
  MelSpectogram to train our model.
Data Preparation - normalized and splited our data for training and testing.

