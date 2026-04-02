# Analysing Data - Assignment 3

## How to use
1. Click the [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/573phn/dh_ad_a3/blob/main/a3.ipynb) button here or in the [`a3.ipynb`](a3.ipynb) file
2. Make sure you're using a runtime with a GPU (Runtime -> Change runtime settings)
3. Click `Run all`

## CSV files
### [`data/genreLyrics_test.csv`](data/genreLyrics_test.csv)
Test data, contains the following columns:
-  ` `: Index column, contains unique IDs of song lyrics
- `genre`: Contains the song's genre
- `lyrics`: Contains the song's lyrics

### [`data/genreLyrics_train.csv`](data/genreLyrics_train.csv)
Training data, contains the following columns:
-  ` `: Index column, contains unique IDs of song lyrics
- `genre`: Contains the song's genre
- `lyrics`: Contains the song's lyrics

### [`results.csv`](results.csv)
Output of the ollama model with zero-shot and few-shot prompting, contains the following columns:
-  ` `: Index column, contains unique IDs of song lyrics
- `zero-shot`: Genre prediction of the zero-shot model
- `few-shot`: Genre prediction of the few-shot model (uses 2 example lyrics with genres)
- `actual`: Actual genre of the song