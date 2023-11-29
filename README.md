# Music Genre Classifier
This repository contains a machine learning model that classifies music into different genres. The model is trained on the GTZAN dataset, which consists of 1000 audio tracks each 30 seconds long. The tracks are divided into 10 genres, each represented by 100 tracks. The genres are: blues, classical, country, disco, hiphop, jazz, metal, pop, reggae, and rock.

## File Structure
The repository is organized as follows:
```
music_genre_classifier/
├── model/
│   ├── model.h5
│   └── model.json
├── model_training/
|   └── model_training.ipynb
├── src/
|   └── predict.py
├── requirements.txt
└── README.md
```

## Usage
1. Clone this repository.
2. Install the required packages using `pip install -r requirements.txt`.
3. Run `python predict.py <filename>` to predict the genre of a music file.

## Results
The model achieves an accuracy of 70% on the test set.
