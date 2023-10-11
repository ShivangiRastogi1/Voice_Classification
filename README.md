# Voice_Classification

# Data Set :

https://www.kaggle.com/datasets/primaryobjects/voicegender

Data Set: Voice Data Set
Gender Recognition by Voice and Speech Analysis
This database was created to identify a voice as male or female, based upon acoustic properties of the voice and speech. The dataset consists of 3,168 recorded voice samples, collected from male and female speakers. The voice samples are pre-processed by acoustic analysis in R using the seewave and tuneR packages, with an analyzed frequency range of 0hz-280hz :

meanfreq: mean frequency (in kHz)
sd: standard deviation of frequency
median: median frequency (in kHz)
Q25: first quantile (in kHz)
Q75: third quantile (in kHz)
IQR: interquantile range (in kHz)
skew: skewness (see note in specprop description)
kurt: kurtosis (see note in specprop description)
sp.ent: spectral entropy
sfm: spectral flatness
mode: mode frequency
centroid: frequency centroid (see specprop)
peakf: peak frequency (frequency with highest energy)
meanfun: average of fundamental frequency measured across acoustic signal
minfun: minimum fundamental frequency measured across acoustic signal
maxfun: maximum fundamental frequency measured across acoustic signal
meandom: average of dominant frequency measured across acoustic signal
mindom: minimum of dominant frequency measured across acoustic signal
maxdom: maximum of dominant frequency measured across acoustic signal
dfrange: range of dominant frequency measured across acoustic signal
modindx: modulation index. Calculated as the accumulated absolute difference between adjacent measurements of fundamental frequencies divided by the frequency range
label: male or female

## Tasks:

* Import Necessary Libraries
* Load Data Set
* Explore Data
* Data Prepration-
* Perform Exploraty Data Analysis
* Perform Feature engineering -Encode Categorical Variables using Label Encoder, Data normalization using StandardScaler
* Split dataset in training and test datasets
* Train model
* Evaluate Models
* Apply MAchine Learning Algorithims - Linear Regression
* Get Root Mean Square Error RMSE (RMSE) and R2 Value/Coefficient of Determination
* Apply Lasso and ElasticNet Algorithims - get predictions from the model and print accuracy, and create a confusion matrix and a classification report
* Perform Parameter Tuning using GridSearch
