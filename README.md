This is the reduced version of the original model with a smaller dataset, as training the full model on the full dataset on a normal computer takes several hours.

To train the model yourself, download BERT_v2_small.ipynb and reddit_data_raw_small.csv, place them in the same folder, and run BERT_v2_small.ipynb from top to bottom to replicate training and analysis of the model on the smaller dataset with hyperparameters set for training speed as opposed to accuracy. 

It will likely take a few minutes to download the BERT model from tensorflow-hub, and will take about four minutes to train the model, and a few minutes to get the classification accuracy for the validation set and to generate predictions for the test set. In its entirety it should take about 10 minutes.
