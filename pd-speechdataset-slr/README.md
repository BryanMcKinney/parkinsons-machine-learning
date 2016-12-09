# pd-speechdataset-skflow

Tensorflow implementation of DNN on parkinson's disease patients.

https://archive.ics.uci.edu/ml/datasets/Parkinson+Speech+Dataset+with++Multiple+Types+of+Sound+Recordings

for tensorboard, run 'tensorboard --logdir=models'

### Attribute information

* column 1: Subject id 
* colum 2-27: features 
* features 1-5: Jitter (local),Jitter (local, absolute),Jitter (rap),Jitter (ppq5),Jitter (ddp), 
* features 6-11: Shimmer (local),Shimmer (local, dB),Shimmer (apq3),Shimmer (apq5), Shimmer (apq11),Shimmer (dda), 
* features 12-14: AC,NTH,HTN, 
* features 15-19: Median pitch,Mean pitch,Standard deviation,Minimum pitch,Maximum pitch, 
* features 20-23: Number of pulses,Number of periods,Mean period,Standard deviation of period, 
* features 24-26: Fraction of locally unvoiced frames,Number of voice breaks,Degree of voice breaks 
* column 28: UPDRS (NOT IN TEST)
* column 29: class information 

Training Dataset 

Each subject has 26 voice samples including sustained vowels, numbers, words and short sentences. The voice samples in the training data file are given in the following order: 

* sample# - corresponding voice samples 
* 1: sustained vowel (aaaâ€¦â€¦) 
* 2: sustained vowel (oooâ€¦...) 
* 3: sustained vowel (uuuâ€¦...) 
* 4-13: numbers from 1 to 10 
* 14-17: short sentences 
* 18-26: words 

### Citation Request:

Please cite the following paper if you use this dataset: 
Erdogdu Sakar, B., Isenkul, M., Sakar, C.O., Sertbas, A., Gurgen, F., Delil, S., Apaydin, H., Kursun, O., 'Collection and Analysis of a Parkinson Speech Dataset with Multiple Types of Sound Recordings', IEEE Journal of Biomedical and Health Informatics, vol. 17(4), pp. 828-834, 2013. 