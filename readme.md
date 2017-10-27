# Convolutional Neural Network on Street View House Numbers Classification

## Procedures to execute the program:

### Step 1: 

Execute the data_preprocessing.ipynb to download, preprocessing downloaded images and generate a preprocessed data file named as SVHN_data.pickle.

### Step 2: 

Execute the data_analysis.ipynb to extract images from SVHN_data.pickle and generate two files named SVHN_weight.ckpt, SVHN_weight.ckpt.meta separately.

### Step 3: 

Execute the prediction_test.ipynb to read in folder named ‘prediction’’s images and read in the file SVHN_weight.ckpt generated in Step 2 then predict prediction images’ results.

## Demo

![demo](https://github.com/woodenleaves/CNN_Street_View_House_Numbers/raw/master/cnn_svhn.png)

## Note:
Prediction folder contains 17 pictures cropped by author himself from Google Street View in Manhattan, New York. All the 17 images have been resized to 32 x 32.


## Environment:

TensorFlow 0.11

Python 2.7

Jupyter Notebook

