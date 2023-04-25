
  

# Recommender System README

  

## Introduction

This project contains a recommender system built using Surprise a Python recommender system library. The project is done for the SDSC3002 Data Mining Class at City University of Hong Kong

  

## Files

  
  

The original project contains the following files (some files are witheld due to the course policy):

1.  `training.txt`: Training data consisting of $u$ $i$ $r_{ui}$

$u$ : user_id

$i$ : item_id

$r_{ui}$ : rating of user $u$ to item $i$

consisting of ~19.9 millions ratings

  

2.  `testing.txt`: Target user_id and item_id for prediction (actual results not shared to students)

  

3.  `1-data_analysis.ipynb`: Code for data analysis, data sampling and experimentation.

3.  `sample_train.csv`: Data sampling of train data

5.  `2-hyperparameter_tuning.ipynb`: Code for SVD hyperparameter tuning on a sample dataset.

6.  `81.csv`: Hypertuning results produced by `hyperparameter_tuning.ipynb`

7.  `3-hypertuning-analysis.ipynb`: Code for analyzing the results of hyperparameter tuning on the sample dataset.

8.  `4-svd-training.ipynb`: Code for training the Singular Value Decomposition (SVD) model on the full dataset.

9.  `5-prediction.ipynb`: Code for predicting ratings on the testing.txt dataset.

10.  `prediction.txt`: Prediction results of the recommender system.

  

## Dependencies

This project requires the following dependencies to be installed:

  

To install the dependencies, run the following command:

  

```pip install -r requirements.txt```

  

## Usage

1. Open the Jupyter notebook `1-data_analysis.ipynb` and run the cells in the notebook in the order they appear.

2. Open the Jupyter notebook `2-hyperparameter_tuning.ipynb` and run the cells in the notebook in the order they appear.

3. Open the Jupyter notebook `3-hypertuning-analysis.ipynb` and run the cells in the notebook in the order they appear.

4. Open the Jupyter notebook `4-svd-training.ipynb` and run the cells in the notebook in the order they appear.

5. Open the Jupyter notebook `5-prediction.ipynb` and run the cells in the notebook in the order they appear.

5. Open the `prediction.txt` file to view the prediction results of the recommender system.

  

Note: The `svd-training.ipynb` notebook may take a while to run, depending on the size of the dataset.

  

## Acknowledgements

This project is done in part of the SDSC3002 Data Mining course at City University of Hong Kong.