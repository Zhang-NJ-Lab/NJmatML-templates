# NJmatML-templates
csv templates for NJmatML

## train/test dataset
Train-test.csv
train-test dataset for machine learning models (the most important part! The left region is the features; the rightmost column is the target output such as Eg, formation energy, photocurrent, etc.)

## virtual space for prediction
Prediction_Unlabelled-RFE13
virtual space teamplate for machine learning prediction (be careful: the number of columns should be the same as the RFE remaining number you entered in the software!!!)

## inorganic variables
Inorganic_Descriptors.csv      
csv template to generate elemental and one-hot features from materials formulas. The column name should be **formula**, otherwise the file can not be recognized by the software.

## organic variables
Organic_descriptor.csv
csv template to generate rdkit features from smiles codes.
