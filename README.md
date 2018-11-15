# Data-Science-Programming
Emotion Detection Using Deep Learning
Steps for executing the project

1.	The folder DSP_Project_Files contains the Dataset folder, Model Python notebook, Testing python Notebook and saved model .h5 file

2.	The Dataset folder “Audio_Speech_Actors_01-24” contains 24 subfolders, in which there were Audio files alone (60 files for each actor) for all emotions.

Note: Two files (“Actor13/03-01-02-01-02-02-13.wav” and “Actor11/03-01-08-01-02-02-11.wav”) were deleted as they are of a different audio duration in our dataset. So, there are a total of 1438 audio files.

3.	For running the code, 
•	First, run the jupyter notebook “Emotional_Intelligence_Model.ipynb” file which has the code for data preprocessing, building and saving the model as “EmotionDetectionModel.h5” in the main folder “DSP_Project_Files”.

Also, the Waveform, Spectogram and Mel-Spectogram plots are saved in the main folder (“DSP_Project_Files”).

Note: 
o	The CNN model takes approximately 4-5 hours to train
o	There is a saved model file with the name “EmotionDetectionModel.h5”, which can be loaded directly for testing.

•	Next, run the jupyter notebook “Emotional_Intelligence_Testing.ipynb” file which has code to load the previously saved model, record a voice and test for various audio files from the existing dataset and also the recorded voice.

After recording, this creates a “Output.wav” audio file in the main folder “DSP_Project_Files”.
