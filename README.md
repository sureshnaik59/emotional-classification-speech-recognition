# emotional-classification-speech-recognition
The dataset consists of audio files of speeches and songs with various emotions.

#  Objective
The objective is to predict the most likely emotion expressed in each audio clip, choosing from the seven emotions provided (neutral, happy, sad, angry, fear, disgust, and surprise) provided in the dataset Build a CNN model to predict the emotion in the audio.

# Data Description
The data contains the various audio files (16bit, 48kHz .wav). The dataset contains 24 professional actors (12 female, 12 male), vocalizing two lexically matched statements in a neutral North American accent. Speech emotions include calm, happy, sad, angry, fearful, surprise, and disgust expressions. Each expression is produced at two levels of emotional intensity (normal, strong), with an additional neutral expression.
# File naming convention
Each file has a unique filename. The filename consists of a 7-part numerical identifier (e.g., 03-01-06-01-02-01-12.wav). These identifiers define the stimulus characteristics:

-- Modality (01 = full-AV, 02 = video-only, 03 = audio-only).
Vocal channel (01 = speech, 02 = song).
Emotion (01 = neutral, 02 = calm, 03 = happy, 04 = sad, 05 = angry, 06 = - fearful, 07 = disgust, 08 = surprised).
Emotional intensity (01 = normal, 02 = strong). NOTE: There is no strong intensity for the 'neutral' emotion.
Statement (01 = "Kids are talking by the door", 02 = "Dogs are sitting by the door").
Repetition (01 = 1st repetition, 02 = 2nd repetition).
Actor (01 to 24. Odd-numbered actors are male, even-numbered actors are female).
Below is a Filename example mentioned below and do refer this as you will extract emotion and perform analysis based upon below examples: 03-01-06-01-02-01-12.wav

Audio-only (03)
Speech (01)
Fearful (06)
Normal intensity (01)
Statement "dogs" (02)
1st Repetition (01)
12th Actor (12)
Female, as the actor ID number is even
