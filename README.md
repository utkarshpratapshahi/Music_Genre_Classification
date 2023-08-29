# Music Genre Classification
## Dataset:
The GTZAN dataset is the most-used public dataset for evaluation in machine listening research for music genre recognition (MGR). The files were collected in 2000-2001 from a variety of sources including personal CDs, radio, and microphone recordings, in order to represent a variety of recording conditions.<br />
link:  https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification<br />
## Feature Extraction:
The first step for this project would be to extract features and components from the audio
files. It includes identifying the linguistic content and discarding noise.
Mel Frequency Cepstral Coefficients:

● These are state-of-the-art features used in automatic speech and speech recognition
studies. There are a set of steps for the generation of these features:

● Since the audio signals are constantly changing, first we divide these signals into
smaller frames. Each frame is around 20-40 ms long

● Then we try to identify different frequencies present in each frame

● Now, separate linguistic frequencies from the noise

● To discard the noise, it then takes discrete cosine transform (DCT) of these
frequencies. Using DCT we keep only a specific sequence of frequencies that have a
high probability of information
## Model Training:

In this project, the K-nearest neighbors algorithm is being used because various prior
research have proved that this algorithm gives the best results for this problem of
classification of music
K-Nearest Neighbour is one of the simplest Machine Learning algorithms based on the
Supervised Learning technique.
it assumes the similarity between the new case/data and available cases and put the new case
into the category that is most similar to the available categories.
K-NN algorithm stores all the available data and classifies a new data point based on the
similarity. This means when new data appears then it can be easily classified into a well suite
category by using K- NN algorithm.

## Prediction:

This step involves using test data to try and predict the genre of the sample music file against
the trained model and gain accuracy parameters.
