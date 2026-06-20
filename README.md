# Stages of Parkinson's Disease: An Analysis of Vocal Recordings
*Project Title for R for Biostatistical Methods Course (PHC 6080)*


Vocal detection is a cost-effective and non-invasive way to monitor Parkinson's disease (PD) over time. While it can be helpful to assisting PD and understanding how vocal recordings can detect PD, there are questions regarding the design for studying vocal recordings. For the analysis, the dataset is the Oxford Parkinson’s Disease Detection Dataset from the UCI Machine Learning Repository. This dataset comprises biomedical voice measurements from 31 individuals, 23 of whom have Parkinson’s disease. There will be two questions to be analyzed:

Can we predict the average vocal frequency of a patient based on micromovements in their vocal stability (such as jitters or shimmers)?

What is the association between the vocal boundaries of a patient and their progression of Parkinson’s disease?

## 📊 **Exploratory Data Analysis**

Variable Descriptions, from the UCI Repository:

name - ASCII subject name and recording number

MDVP:Fo(Hz) - Average vocal fundamental frequency

MDVP:Fhi(Hz) - Maximum vocal fundamental frequency

MDVP:Flo(Hz) - Minimum vocal fundamental frequency

MDVP:Jitter(%),MDVP:Jitter(Abs),MDVP:RAP,MDVP:PPQ,Jitter:DDP - Several measures of variation in fundamental frequency

MDVP:Shimmer,MDVP:Shimmer(dB),Shimmer:APQ3,Shimmer:APQ5,MDVP:APQ,Shimmer:DDA - Several measures of variation in amplitude

NHR,HNR - Two measures of ratio of noise to tonal components in the voice

status - Health status of the subject (one) - Parkinson's, (zero) - healthy

RPDE,D2 - Two nonlinear dynamical complexity measures

DFA - Signal fractal scaling exponent

spread1,spread2,PPE - Three nonlinear measures of fundamental frequency variation

For this analysis, the following variables will be used: MDVP:Fhi, MDVP:Jitter, MDVP:Shimmer, MDVP: Flo, NHR, HNR, status, MDVP:Fo, RPDE, DFA, PPE.

