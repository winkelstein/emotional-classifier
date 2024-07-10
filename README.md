# emotional-classifier

## Model

LSTM neural network using Pytorch.

```
EmotionalLSTM(
  (embedding): Embedding(129928, 256)
  (lstm): LSTM(256, 512, num_layers=2, batch_first=True, dropout=0.25)
  (dropout): Dropout(p=0.3, inplace=False)
  (fc): Linear(in_features=512, out_features=2, bias=True)
  (sigmoid): Sigmoid()
)
```

## Dataset

This project uses IMDB dataset for sentiment analysis from Kaggle ([link](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)).

## Project structure

```
emotional-classifier/
│
├── data/
│   └── IMDB.csv
│
├── notebooks
│   └── lstm.ipynb
│
├── README.md
└── requirements.txt
```
