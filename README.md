# Pima-Indians-diabetes
This dataset describes the medical records for Pima Indians and to check whether or not each patient will have an onset of diabetes within few years

About this file This dataset describes the medical records for Pima Indians and whether or not each patient will have an onset of diabetes within few years.

Fields description follow:

preg = Number of times pregnant

plas = Plasma glucose concentration a 2 hours in an oral glucose tolerance test

pres = Diastolic blood pressure (mm Hg)

skin = Triceps skin fold thickness (mm)

test = 2-Hour serum insulin (mu U/ml)

mass = Body mass index (weight in kg/(height in m)^2)

pedi = Diabetes pedigree function

age = Age (years)

class = Class variable (1:tested positive for diabetes, 0: tested negative for diabetes)

## Libraries Used
 numpy
 pandas
 matplotlib.pyplot
%matplotlib inline
seaborn 
 sklearn.model_selection import train_test_split
 sklearn.metrics import confusion_matrix
 sklearn import metrics
 
 ## Summary :
We successfully analysed the Pima-Indians-diabetes data set and ploteed Receiver Operating Characteristic (ROC) Curves Model 2 with Treshold of 0.3 and Sensitivity: 0.8, Specificity: 0.7671232876712328 is the best fit
