# LegoBricksClassificationCNN
Jupyter Notebook for 1st homework of the Knowledge Discovery course at UniCT

## Description

A deep model that consists of 2 Convolutional Layers, to extract and recognize increasingly complex features, followed by a Fully Connected Layer and a Classifier to perform multiclass classification (see Fig. 1).  Initially, input data flows trough the convolutional layers, to extract image features. Then the extracted features are provided to the fully connected layers and to the classifier, which predicts the class outcome among one of the 16 possible classes.
<img width="1050" alt="LegoBricksNet" src="https://user-images.githubusercontent.com/64035952/164468926-b126d10b-1017-447a-b820-a4a470949ca5.png">

## Dataset
Data I have used:

_The archive will be uploaded in the next commit_

These data are taken from Kaggle:

https://www.kaggle.com/datasets/joosthazelzet/lego-brick-images

The data splitting is directly performed on the script, within the data trasform process.

## Usage

Upload the dataset provided and the .ipynb notebook on your Google Drive.

Open the .ipynb notebook on Google Colaboratory, and you will be able to run the cells.

You will find all the networks on the same jupyter notebook.

## Contacts
Francesco Pappalardo - pappalardofg@outlook.it

Vanessa Perticone - vanessaperticone12@gmail.com
