# Urban Sound Classification
This is an audio classification project that classifies various sounds using their unique spectrogram into multiple classes such as Dog Barking, Sirens, Street Music etc using Neural Networks

## Description

* The UrbanSound8k dataset contains 8732 labelled sound excerpts (<=4s) of urban sounds from 10 classes: air_conditioner, car_horn, children_playing, dog_bark, drilling, enginge_idling, gun_shot, jackhammer, siren, and street_music. The classes are drawn from the urban sound taxonomy.

* 8732 audio files of urban sounds (see description above) in WAV format. The sampling rate, bit depth, and a number of channels are the same as those of the original file uploaded to Freesound (and hence may vary from file to file).
The UrbanSound8k dataset used for model training can be downloaded from the following link: https://urbansounddataset.weebly.com/

### Librosa
Librosa is a python package for music and audio analysis. It provides the building blocks necessary to create music information retrieval systems. It is used for data pre-processing and feature extraction. Features used:
##### MFCC

* The Mel-Frequency Cepstral Coefficients (MFCC) summarises the frequency distribution across the window size, so it is possible to analyze
both the frequency and time characteristics of the sound. These audio representations will allow
us to identify features for classification. It will try to convert the audio into some kind of feature based on the frequency and time characteristics which will help us to do the classification.

* MFCC does nothing but extract patterns based on the frequency and time characteristics. This will uniquely able to identify that particular audio signal like in which class it actually belongs because this audio signal will be later used in deep learning Techniques.

#### Conclusion

* The Testing Accuracy comes out to be: 78.82%


### Technology Used

* Artificial Neural Networks
* Librosa
* Scipy
* Mel-Frequency Cepstral Coefficients(MFCC)
* TensorFlow
* keras
* NumPy
* pandas

