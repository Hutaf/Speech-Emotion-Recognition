# Speech Sentiment Analysis

Inline-style: 
![Speech Sentiment Analysis](https://www.sri.com/wp-content/uploads/2019/09/OTO-v1-940x373.png)


Social media one of the most powerful sources for information due to the tremendous amount of data generated by them. These platforms are full of thoughts, emotions, and feedbacks related to many real-life events; people depict their opinions about products, movies, social issues, political issues,
etc. This has led to a huge amount of projects focus on identifying the hidden knowledge and the emotions behind these data. Sentiment analysis is a refernce to the task in natural language processing (NLP) that aims to identify emotions underlying the written texts as we humans do, by measuring the text polarity if it is positive or negative.But audio sentiment analysis is still in a nascent stage in the research community. The capability of detecting the sentiment of the speaker in the video
Speech emotion recognition (SER) systems defined  as a collection of methodologies that process and classify speech signals to detect the embedded emotions. 

In this Project, I aaplied techniques to detect speech emotions such as happiness, sadness, fear, and angry etc. with machine learning and neural networks. Earlier repoistries covered classification problems where data can be easily expressed in vector form. For example, in thefake news detection, each word in the corpus becomes feature and tf-idf score becomes its value. But when it comes to audio, feature extraction is not quite straightforward. Here, I will first see what features can be extracted from the speech dataset and how it will be extracted in Python using open source library called Librosa.


 
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
CNN | | | |
CNN-LSTM | | | |


## Summary

## How to use the code?


