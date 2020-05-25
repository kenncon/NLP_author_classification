The files in this github are:

BERT_v2.ipynb

reddit_data_raw.csv

BERT_v2_small.ipynb

reddit_data_raw_small.csv



BERT_v2.ipynb and reddit_data_raw.csv are the full model with optimally tuned hyperparameters and the full dataset respectively. Uploading the files that constitute the trained full model are too large for either github or dropbox, though are available on request through other means if necessary. Training the full model on your computer would likely take several hours, and is thus not recommended.

Instead, for local running of the code, downloading just BERT_v2_small.ipynb and reddit_data_raw_small.csv, placing them in the same folder, and running BERT_v2_small.ipynb from top to bottom will replicate training and analysis of the model on a smaller dataset with hyperparameters set for training speed as opposed to accuracy. 

It will likely take a few minutes to download the BERT model from tensorflow-hub, and will take about four minutes to train the model, and a few minutes to get the classification accuracy for the validation set and to generate predictions for the test set. In its entirety it should take about 10 minutes.
