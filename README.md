Real Time Pubg audio was classified by using Tensorflow coco model 
Ideas:
 The core idea of this project is to classify the audio by mel-spectrogram frequency. In this project the audio was first recored and then converted that audio into 
 mel-spectrogram image for classifying the audio by frequency image.
Steps:
1.Recorded the four types of pubg game sound in 10sec's
2.Converted that the audio file into mel-spectrogram by using librosa, scipy and matplotlib
3.Lable the mel-spectrogram image according the sounds by using labelImg python open source tools
4.And clubed all the mel-spectrogram images into one video file for classification
5.Build the model using tensorflow2.0 and coco model ssd640x640
6.Classify the audio by using OpenCV.
