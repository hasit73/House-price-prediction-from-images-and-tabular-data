# House-price-prediction-from-images-and-tabular-data

House price estimation by building hybrid model which accept both image and textual data. i had build CNN + ANN model that perform really well on House Dataset. 

### Library required:

- opencv = 4.5.4-dev'
- tensorflow = '2.6.0'
- pandas = '1.1.5'
- scikit-learn = '0.24.2'

### Download Dataset:

1) Text data HouseInfo.txt which i already uploaded in this repo

2) House Dataset (Images data) you can download from here : _**House Dataset**_[https://www.kaggle.com/amir22010/house-price]

# Quick Overview about structure

#### 1) data-preparation.ipynb

- Load text data and do feature engineering
- load image data and stitching them(4 different category images of particular house) as single image.


#### 2) model-building.ipynb

- split data into train and test data
- create hybrid structure of ANN + CNN model
- train model and select best one.


#### Model architecture




# How to use 

1) clone this directory

2) open _**data-preparation.ipynb**_ and exceute all cells  and at the end you have two files _**Images-numpy.npy**_ and _**Text-numpy.npy**_

3) open _**model-building.ipynb**_ and exceute all cells , traning Hybrid model may take long time that's depends on your hardware system
