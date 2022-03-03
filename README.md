UPDATES:
03/03/22 -  reduce_noise inputs have been corrected 
            QA printing added due to np.pad issues: filename, length, & dBFS when needed.

# Speech Emotion Recognition (SER) in real-time
A Deep Learning (LSTM) model with keras.

This study aims to investigate and implement an Artificial Intelligence (AI) algorithm that will analyze an audio file in real-time, identify and present the expressed emotion within it.

A classification model is developed in a Deep Learning method, meaning a Deep Neural Network (DNN) while an advanced model for time-series analysis has been chosen, which is the Long Short-Term Memory (LSTM).

For the train of the model, expressed emotions by actors have been used from The Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS) from the Ryerson University, as well as the Toronto Emotional Speech Set (TESS) from the University of Toronto. 

Results had shown an accuracy of 87% of emotional recognition from speech.
A real-time implementation of the model is executed, receiving microphone signal as input and analyzing it cyclicly, outputs the distribution of emotions expressed every time cycle. When recognizing silence of 2 seconds or more, the system autonomously stops.
