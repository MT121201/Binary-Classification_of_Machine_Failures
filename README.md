# Binary-Classification_of_Machine_Failures
Kaggle Playground Series - Season 3, Episode 17\
All datasets in this repository is from Kaggle, https://www.kaggle.com/competitions/playground-series-s3e17/overview
## Dataset Description
The dataset for this competition (both train and test) was generated from a deep learning model trained on the Machine Failure Predictions. Feature distributions are close to, but not exactly the same, as the original. Feel free to use the original dataset as part of this competition, both to explore differences as well as to see whether incorporating the original in training improves model performance.
## Details about the dataset:
- Product ID: Product ID, which represents categorical data, is a key feature used to distinguish the type of product processed and consists of a letter Low (50%), medium (30%), High (20%) as product quality variants.
- Air temperature (K): Air temperature, which represents numerical data, refers to the temperature of the environment (between 2 K and 300 K after normalization).
- Process temperature (K): Process temperature, which represents numerical data, refers to the temperature of the production process.
- Rotational speed (rpm): Rotational speed, which represents numerical data, refers to the rotational speed of the main shaft.
- Torque (Nm): Torque represents a type of numerical data and is generally equal to 40 Nm where ε = 10 and no negative values.
- Tool wear (min): Tool wear, which represents numerical data, refers to the tool operation time.
- The six equipment fault features of the data points are as follows:
- Tool wear failure (TWF): Tool wear failure causes a process failure.
- Heat dissipation failure (HDF): Heat dissipation causes a process failure.
- Power failure (PWF): Power failure causes a process failure.
- Overstrain failure (OSF): OSF refers to the failure caused by overstrain in the production process.
- Random failures (RNF): RNFs are failures whose cause cannot be determined. Their occurrence probability in the production process is 0.1%.
- Machine failure: The original two-category label (0 represents normal, and 1 represents failure)
## Files
train.csv - the training dataset; Machine failure is the (binary) target (which, in order to align with the ordering of the original dataset, is not in the last column position)

test.csv - the test dataset; your objective is to predict the probability of Machine failure

sample_submission.csv - a sample submission file in the correct format

## API command
kaggle competitions download -c playground-series-s3e17
