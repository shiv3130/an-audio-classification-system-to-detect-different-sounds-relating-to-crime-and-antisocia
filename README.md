# an-audio-classification-system-to-detect-different-sounds-relating-to-crime-and-antisocia
research  and  develop  an  implementation  plan  for  an  audio  classification  system  to  detect  different  sounds  relating  to  crime  and antisocial behaviour. In this coursework you are required to implement your solution using the  Keras and TensorFlow.
Detail of the tasks
1) Data pre-processing
In this task, you are required to pre-process an audio dataset in order to train a model capable of 
classifying a selection of different sounds. The sounds you choose (classes) are up to you, but you 
should consider the problem outlined in the first coursework. All tasks should be undertaken in 
Jupyter Lab with a description of each cell using markdown. 
 Using the audio dataset (Audio.zip) on Canvas, you are required to load the audio data 
set. 
 Include visualisations of the audio files such as wave plots etc.
 Extract the features using an appropriate technique from either the 
python_speech_features or librosa package and use features such as Mel-Frequency 
Cepstral Coefficients (MFCC). A full list of available feature extraction methods for the 
APIs can be found here: https://python-speech-features.readthedocs.io/en/latest/, 
https://librosa.org/doc/main/feature.html#feature
 Use an appropriate technique to decide which features are important to train the model.
 Using the generated data, you are required to generating an appropriate 
train/test/validation split.
2)  Model development and training  
In this task, you are required to train an audio classification model using the pre-processed data from 
task 1. The model architecture and hyperparameters you choose to perform the training is up 
to you; however, you must provide justification for your selection in the markdown. Using your 
pre-processed data construct a Jupyter notebook to achieve the following:
 Configure network architecture (while providing justification).
 Train your model for a set number of epochs. The number you choose is up to you, but you 
should consider overfitting, model accuracy and techniques such as early stopping. You will 
need to provide justification for the number of epochs used.
  
3) Model evaluation and deployment
In this task you are required to evaluate your model using a variety of different metrics. 
 For this task you must undertake the following steps:
 Return  the  confusion  matrix,  sensitivity,  specificity,  loss  and  AUC  values  to  determine  the 
performance of the trained model.
 Save your model in the .h5 format once you are happy with the results.
 Develop a Jupyter Notebook to perform inference on your .h5 model using unseen test audio 
files. 
 At the end of your Jupyter Notebook in markdown discuss your results.
