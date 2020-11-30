# Speech Emotion Recognition

Speech is the most natural way of expressing ourselves as humans. It is only natural then to extend this communication medium to computer applications. Speech emotion recognition (SER) systems defined  as a collection of methodologies that process and classify speech signals to detect the embedded emotions. 
 
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
