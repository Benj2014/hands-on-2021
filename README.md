# Hands-on-2021

Build a model and an interface to classify traffic signs (GTSRB dataset).

## 1-Install

* clone this repository 
* download images with `scripts/download_images.sh`

## 2-Additional comments

This project will be done using a neural network and a SVM model for classifying the pictures.

Our project is made for up 5 steps :

1-Data preparation
  1-1-Feading of data
  1-2-Constiution of train and test group

2-Model training
    2-1-Neural network model
Do that on google colab and use the TPU process to faster the training of the model. 
Use Tensorflow and keras for that
    2-2-SVM model

3-Model saving
    2-1-Neural network 
 It has been saved in.h5 in order to be able load and use thatfor future images predictions
    2-2-SVM
It has to be saved in pickle for the same reason

4-create of a web application allowing to download a picture of our dataset and predict it
Use Dash for that. But there exist other tools for that like bokeh and streamlit in python.We can use Shiny in R

5-Measure the model performance
 
## 3-References

* Dataset introduction: https://benchmark.ini.rub.de/gtsrb_dataset.htm
* Images: https://sid.erda.dk/public/archives/daaeac0d7ce1152aea9b61d9f1e19370/published-archive.html