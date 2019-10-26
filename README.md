# Human Activity Recognition Using Long Short Term Memory Networks
Implementation of Recurrent Neural Networks on time-series Data

## Install
This project is built using Python and the following Python libraries:
- Numpy
- Pandas
- Keras
- Scipy

As this is a ipynb file, you will need a software to run the [Jupyter Notebook](https://github.com/sriganeshlokesh/human_activity_recognition_lstm_keras/blob/master/HAR_LSTM.ipynb)

If Python is not installed on your computer, it is highly recommended to install [Anaconda Distribution](https://www.anaconda.com/distribution/)
The Anaconda Distribution contains all the above packages and more installed.

## Code

The notebook file for this project is `HAR_LSTM.ipynb`. this contains code for building and training the neural network. we have used Keras to build and train the model. 

## Run

In a terminal or command window, run the following commands:
```python
jupyter notebook HAR_LSTM.ipynb
```
or

```python
ipython notebook HAR_LSTM.ipynb
```
This will open the Jupyter Notebook software and project file in your web browser.

## Data

Dataset used in this project is `WISDM_ar_v1.1_raw.txt` from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones).

We will train a recurrent neural network (RNN) using Long Short Term Memory Networks to recognize the type of movement (Walking, Sitting, Standing, Upstairs and Downstairs) based on a given set of accelerometer data from a mobile device carried around a person’s waist.

#### Features:

`user-id`: unique id given to the person performing the activity.

`activity`: Target variable detecting the type of activity the user is performing.

`timestamp`: unique timestamp given to each movement.

`x-axis`: x-axis values from the accelerometer.

`y-axis`: y-axis values from the accelerometer.

`z-axis`: z-axis values from the accelerometer.
