# heartbeat_ECG_signals
 Identify healthy heartbeat and anomalies in heartbeat from ECG signals - Binary classification. 


# Heartbeat Classification using Random Forest

This repository contains Python code for classifying heartbeat signals into different categories using a Random Forest classifier. The dataset used for training and testing the model is sourced from the MIT-BIH Arrhythmia Database.

## Requirements

Make sure you have the following libraries installed:

- pandas
- numpy
- matplotlib
- scikit-learn
- seaborn

You can install these dependencies using the following command:

```bash
pip install pandas numpy matplotlib scikit-learn seaborn
```

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/heartbeat-classification.git
   ```

2. Navigate to the project directory:

   ```bash
   cd heartbeat-classification
   ```

3. Run the Jupyter notebook or Python script to execute the code.

## Dataset

The MIT-BIH Arrhythmia Database is used for training and testing the Random Forest classifier. The dataset is loaded from the following files:

- Training dataset: `/content/drive/MyDrive/HeartBeat/mitbih_train.csv/mitbih_train.csv`
- Testing dataset: `/content/drive/MyDrive/HeartBeat/mitbih_test.csv/mitbih_test.csv`

## Data Preprocessing

- The dataset is loaded and checked for missing values.
- Any rows with missing values are dropped to ensure a clean dataset.

## Model Training and Evaluation

1. The dataset is split into training and testing sets.
2. A Random Forest classifier is initialized with 100 estimators and a random state of 42.
3. The model is trained on the training set and evaluated on the testing set.
4. Metrics such as accuracy, precision, recall, and confusion matrix are calculated and printed.

## Results Visualization

- The confusion matrix for the testing data is visualized using a heatmap.
- ECG signals for a sample from both the training and testing datasets are plotted for visual inspection.
