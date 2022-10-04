# Genre_Recognition
Prediction of music genre recognition with machine learning

### Overview

The goal of this project is to build and critically analyse some supervised Machine Learning algorithms, to
automatically identify the genre of a song on the basis of its audio, metadata and textual features. That is, given
a list of songs, I will implement some Machine Learning model(s), train them using the training
dataset, and evaluate using the test validation and test dataset.

### Dataset

Each song (instance) is represented through a large set of features (described in detail in the Data_description.txt), and
listed in the features.csv files. Each song is labelled with a single genre tag, which is provided in the labels.csv
files.
There is a set of training, validation and test instances.
The files are provided in csv format, which stands for comma-separated values.
* train features.csv: Contains features of 7678 training instances.
* train labels.csv: Contains a single genre label for each training instance
* valid features.csv: Contains features of 450 validation instances.
* valid labels.csv: Contains a single genre label for each validation instance.
* test features.csv: Contains features of 428 test instances.

Each song in the data set is indexed with a unique trackID. We provide three different types of features.
Details are provided in the Data_description.txt file, as well as the references listed under Terms of Use:
* Metadata features: For each song, we provide its title, loudness, tempo, key, mode,
duration, and time_signature .
* Text features: For each song, we provide a list of tags representing the words that appeared in
the lyrics of the song and are human annotated (such as ‘dance’, ‘love’, or ‘never).
* Audio features: We provide 148 pre-computed audio features that were pre-extracted from the
30 or 60 second snippets of each track, and capture timbre, chroma, and ‘Mel Frequency Cepstral Coefficients’ (MFCC) aspects of the audio. Each feature is continuous and the values are not interpretable.
Each song is labelled with its genre, i.e., with a single label from one of 8 possible genre labels:
‘Soul and Reggae’, ‘Pop’, ’Punk’, ‘ Jazz and Blues’, ‘Dance and Electronica’, ‘Folk’, ‘Classic
Pop and Rock’, ‘Metal’
