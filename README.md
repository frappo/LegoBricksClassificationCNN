# Lego Bricks Classification through Convolutional Neural Network
Neural Network built for Image Classification Task d
1st homework of the Knowledge Discovery course at UniCT

## Description

A deep model that consists of 2 Convolutional Layers, to extract and recognize increasingly complex features, followed by a Fully Connected Layer and a Classifier to perform multiclass classification (see Fig. 1).  Initially, input data flows trough the convolutional layers, to extract image features. Then the extracted features are provided to the fully connected layers and to the classifier, which predicts the class outcome among one of the 16 possible classes.
<img width="1050" alt="LegoBricksNet" src="https://user-images.githubusercontent.com/64035952/164648784-2a6c9af4-851c-4850-85c4-2c9b2669a654.png">


## Dataset
Data I have used:

https://drive.google.com/file/d/1VyPhAiXr2kpMxB5VbzcuFMRjwSEEVfnl/view?usp=sharing

These data are taken from Kaggle:

https://www.kaggle.com/datasets/joosthazelzet/lego-brick-images

The data splitting process is directly performed on the script, within the data trasform process.

## Usage

Upload the dataset provided and the .ipynb notebook on your Google Drive.

Open the .ipynb notebook on Google Colaboratory, and you will be able to run the cells.

You will find all the networks on the same jupyter notebook. In order to have a better automated experience, the script is built with the scope to train all the networks and then to compare them and choose the one who gives you the best Test Accuracy and evaluate it through a Confusion Matrix.

## Contacts
Francesco Pappalardo - pappalardofg@outlook.it

Vanessa Perticone - vanessaperticone12@gmail.com

## Notebook
https://colab.research.google.com/drive/1C7bVOv55_auuCWDkHCyBKfHWaxbVSuuJ#scrollTo=ZiOkkINxCmOt
