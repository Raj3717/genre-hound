# Music Genre Classifier
This repository contains a machine learning model that classifies music into different genres. The model is trained on the GTZAN dataset, which consists of 1000 audio tracks each 30 seconds long. The tracks are divided into 10 genres, each represented by 100 tracks. The genres are: blues, classical, country, disco, hiphop, jazz, metal, pop, reggae, and rock.

## Requirements
- Python 3.6 or later
- TensorFlow 2.0 or later
- NumPy
- SciPy
- Librosa

## Usage
1. Clone this repository.
2. Install the required packages using `pip install -r requirements.txt`.
3. Run `python predict.py <filename>` to predict the genre of a music file.

## Results
The model achieves an accuracy of 70% on the test set.

## License
