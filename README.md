# Binary-Classification_of_Machine_Failures
Kaggle Playground Series - Season 3, Episode 17
All datasets in this repository is from Kaggle, https://www.kaggle.com/competitions/playground-series-s3e17/overview
## Dataset Description
The dataset for this competition (both train and test) was generated from a deep learning model trained on the Machine Failure Predictions. Feature distributions are close to, but not exactly the same, as the original. Feel free to use the original dataset as part of this competition, both to explore differences as well as to see whether incorporating the original in training improves model performance.

## Files
train.csv - the training dataset; Machine failure is the (binary) target (which, in order to align with the ordering of the original dataset, is not in the last column position)

test.csv - the test dataset; your objective is to predict the probability of Machine failure

sample_submission.csv - a sample submission file in the correct format

## API command
kaggle competitions download -c playground-series-s3e17
