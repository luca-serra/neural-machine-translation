# Neural Machine Translation
This program is able to automatically translate sentences from French to English using a neural network trained on 10,000 pairs of sentences written in both languages. The architecture used is an encoder-decoder LSTM (Long Short-Term Memory) network.

## Requirements
You can install the requirements using `pip install -r requirements.txt`.

## Data
The dataset used is available on the Data folder. It is taken from the [ManyThings.org](http://www.manythings.org/anki/) website. The dataset contains more than 150,000 pairs of French & English sentences. However, for the sake of time in the trial-and-error phase of the program's development, only 10,000 of those were used.


## Usage
Run the python file `main.py`.
This will:
* give an insight into the data after the cleaning by printing the first few lines, 
* then train the model on the cleaned data (it may take up to 10min). 
* Finally, it will print the [BLEU score](https://en.wikipedia.org/wiki/BLEU) for the model on both training and test set as well as an insight into the translations made by printing a sample of the predictions. 
