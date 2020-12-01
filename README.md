# Speech Sentiment Analysis

![Speech Sentiment Analysis](https://www.sri.com/wp-content/uploads/2019/09/OTO-v1-940x373.png)


In this Project, I aaplied techniques to detect speech emotions such as happiness, sadness, fear, and angry etc. with machine learning and neural networks. My earlier work covered classification problems where data can be easily expressed in vector form. For example, in the [fake news detection](https://github.com/Hutaf/Fake-News-Detection), each word in the corpus becomes feature and tf-idf score becomes its value. But when it comes to audio, feature extraction is not quite straightforward. Here, I will first see what features can be extracted from the speech dataset and how it will be extracted in Python using open source library called Librosa.


 
## Dataset

For this project, the dataset used is the Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS) dataset on [Kaggle](https://www.kaggle.com/uwrfkaggler/ravdess-emotional-speech-audio)
The data contains 1440 speech files and 1012 Song files from RAVDESS. This dataset includes recordings of 24 professional actors (12 female, 12 male), vocalizing two lexically-matched statements in a neutral North American accent.

Speech includes:
* Calm
* Happy
* Sad
* Angry
* Fearful
* Surprise
* Disgust 

Each file was rated 10 times on emotional validity, intensity, and genuineness. Ratings were provided by 247 individuals who were characteristic of untrained adult research participants from North America.

## Feature Extraction

To extract the useful features from the sound data, we will use Librosa library. It provides several methods to extract a variety of features from the sound clip. We are going to use below mentioned methods to extract various features:

1. mfcc: Mel-frequency cepstral coefficients, represents the short-term power spectrum of a sound.
2. Chorma: Compute a chromagram from a waveform or power spectrogram
3. spectral_contrast: Compute spectral contrast.
4. mel: Mel Spectrogram Frequency
5. Tonnetz: Computes the tonal centroid features (tonnetz).

## Data Visualization
## Baseline Models - Machine Learning Models
Algorithm | **Accuracy** | Recall | Precision | F1-Score
--------- | -------------| -------|-----------|---------
MLP | | | |
Decision Tree | | | |
SVM | | | |

## Deep Learining Model
Algorithm | **Accuracy** | Recall | Precision | F1-Score
--------- | -------------| -------|-----------|---------
NN | | | |
CNN | | | |


## Summary


