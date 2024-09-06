# Predicting Birthweights of Newborns in PyTorch
This project involves predicting the birth weights of newborn babies based on various biological and socioeconomic factors.
Deep Learning is an emerging branch of machine learning that intends to learn the underlying relationships between variables in data
through an extensive training process with the help of a mathematical framework called a Neural Network.

## Dataset
The National Center of Health Statistics of the United States Government published the dataset used in this project in 2018.
The dataset contains millions of records and many features/columns, but only a few were needed to make powerful predictions.
The dataset can be downloaded from this repository or can be viewed online along with the user guide at the website: https://www.cdc.gov/nchs/data_access/vitalstatsonline.htm#Tools 

## Exploratory Data Analysis
Exploratory Data Analysis revealed that the dataset was not clean enough for our needs and required further refinement, which is what the first half of the notebook does.
Unnecessary columns were removed, features were normalized, and missing values were replaced with the most appropriate central statistic.
Some features had to be converted into numerical datatypes to be compatible with the regression model.
The entire procedure, including the reasoning for each decision process, has been included in the notebook.

## The model
The Machine Learning model architecture consisted of 4 fully connected linear layers, including 1 output layer.
Many other architectures were tried, but this architecture showed the best convergence.
The Adam optimizer was used with the Mean Squared Error as the loss metric.
A Learning Rate Scheduler was also employed, starting at a learning rate of 0.001, but no changes were required during the training phase.

## Results
![image](https://github.com/user-attachments/assets/b0c6b47f-b362-4bfc-8ebb-598466f6d55e)
The model converged with a Mean Squared Error of around 225000, i.e., a 470-gram error margin. An interesting insight gained from the results would be to model the problem as a classification
problem rather than a regression problem, due to the MSE value on the validation dataset.

## Downloading Files
All files used in the project including the datasets before and after cleaning, the model and the notebook have been included in the repository.
Please cite this work appropriately if you intend to use these files in your project or work.


All Rights Reserved
© 2024 Abhishek Senthil Kumar.

If you use this model in your research or work, please cite the following:

Abhishek Senthil Kumar. (2024). Newborn Birth Weight Prediction using Deep Learning in PyTorch. https://github.com/Abhi-61/Predicting-Birthweights-of-Newborns-in-pyTorch



