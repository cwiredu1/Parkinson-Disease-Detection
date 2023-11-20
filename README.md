![image description]([C:\Users\charl\OneDrive\Desktop\DATA\parkinson_disease_brain.Jpg](https://i0.wp.com/post.medicalnewstoday.com/wp-content/uploads/sites/3/2021/05/GettyImages-685870788_header-1024x575.jpg?w=1155&h=1528))
# Parkinson-Disease-Detection Using Machine Learning
The objective of this projects is to build a model to accurately detect the presence of Parkinson’s disease in an individual.

# Overview:
Parkinson's Disease (PD) is a neurodegenerative disease which affects, movement, posture and agility. It involves the gradual loss of dopamine producing neurons in the substantia nigra of the brain which severely affects, fine motor movement, posture, muscular dexterity and strength. Long before Parkinson's is officially diagnosed, a myriad of symptoms start to appear. The earliest ones are trouble having control over fine motor movement like drawing figures and shapes.

# Dataset:

Dataset Used : Parkinsons Disease Dataset

Dataset Source : UCI Machine Learning Repository

Dataset Hosting URL : https://archive.ics.uci.edu/ml/machine-learning-databases/parkinsons/parkinsons.data

This dataset is composed of a range of biomedical voice measurements from 31 people, 23 with Parkinson's disease (PD). Each column in the table is a particular voice measure, and each row corresponds to one of 195 voice recordings from these individuals ("name" column). The main aim of the data is to discriminate healthy people from those with PD, according to the "status" column which is set to 0 for healthy and 1 for PD. The data is in ASCII CSV format. The rows of the CSV file contain an instance corresponding to one voice recording. There are around six recordings per patient, the name of the patient is identified in the first column.

# Attribute Information
* name - ASCII subject name and recording number
* MDVP:Fo(Hz) - Average vocal fundamental frequency
* MDVP:Fhi(Hz) - Maximum vocal fundamental frequency
* MDVP:Flo(Hz) - Minimum vocal fundamental frequency
* MDVP:Jitter(%), MDVP:Jitter(Abs), MDVP:RAP, MDVP:PPQ, Jitter:DDP - Several measures of variation in fundamental frequency
* MDVP:Shimmer,MDVP:Shimmer(dB),Shimmer:APQ3,Shimmer:APQ5,MDVP:APQ,Shimmer:DDA - Several measures of variation in amplitude
* NHR, HNR - Two measures of the ratio of noise to tonal components in the voice
* status - The health status of the subject (one) - Parkinson's, (zero) - healthy
* RPDE, D2 - Two nonlinear dynamical complexity measures
* DFA - Signal fractal scaling exponent
* spread1,spread2,PPE - Three nonlinear measures of fundamental frequency variation

# Implementation:
Libraries: NumPy pandas sklearn Matplotlib

# Best Performing Machine Learning Model
SVM Classifier was found to be the best performing Classifier with:

    Accuracy: 0.983051
    F1 Score : 0.980392
    R2 Score : 0.931235

