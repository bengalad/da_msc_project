# bitcoin-sentiment-analysis-predictor
Bitcoin price predicter using historical market data and twitter data, utilising deep learning and sentiment analysis

## Sentiment Analysis Models
### Instructions
Install required packages (Conda environment recommended)

Set data_dir in the notebook to appropriate directory

Will also need to set location to save pickle file of trained model

Add all required files into this directory

Change device with DEVICE = torch.device('...'). I would recommend using google Colab if you don't have access to a local GPU

### Required Files
bitcoin_tweets1000000.csv, from https://www.kaggle.com/datasets/gautamchettiar/bitcoin-sentiment-analysis-twitter-data?resource=download (or any file in format of code for sentiment analysis)

The preprocessed data can be found: TBC

Emoji Dictionary Emoji_Dict.p, from https://www.kaggle.com/datasets/divyansh22/emoji-dictionary-1?resource=download

Slang Dictionary created from https://www.kaggle.com/code/nmaguette/up-to-date-list-of-slangs-for-text-preprocessing/notebook

GloVe Vectors glovee.6B.100d.txt, from https://nlp.stanford.edu/projects/glove/

### Required Packages
Pytorch (tested on 2.0.1+cu118)

NLTK

Scikit-learn

Numpy

Matplotlib (for plotting results)

Tabulate (for printing results)

Tqdm (for progress bars)

## Bitcoin Price predictor
