# pd-telemonitoring-skflow

Tensorflow implementation of Simple Linear Regression on parkinson's disease patients.

Dataset Source: https://archive.ics.uci.edu/ml/datasets/Parkinsons+Telemonitoring

for tensorboard, run 'tensorboard --logdir=models'

#### Attribute Information:

* subject# - Integer that uniquely identifies each subject 
* age - Subject age 
* sex - Subject gender '0' - male, '1' - female 
* test_time - Time since recruitment into the trial. The integer part is the number of days since recruitment. 
* motor_UPDRS - Clinician's motor UPDRS score, linearly interpolated 
* total_UPDRS - Clinician's total UPDRS score, linearly interpolated 
* Jitter(%),Jitter(Abs),Jitter:RAP,Jitter:PPQ5,Jitter:DDP - Several measures of variation in fundamental frequency 
* Shimmer,Shimmer(dB),Shimmer:APQ3,Shimmer:APQ5,Shimmer:APQ11,Shimmer:DDA - Several measures of variation in amplitude 
* NHR,HNR - Two measures of ratio of noise to tonal components in the voice 
* RPDE - A nonlinear dynamical complexity measure 
* DFA - Signal fractal scaling exponent 
* PPE - A nonlinear measure of fundamental frequency variation 

#### Citation Request:

If you use this dataset, please cite the following paper: 
A Tsanas, MA Little, PE McSharry, LO Ramig (2009) 
'Accurate telemonitoring of Parkinson’s disease progression by non-invasive speech tests', 
IEEE Transactions on Biomedical Engineering (to appear). 