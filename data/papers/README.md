# Papers

Heart rate variability has been studied as an indicator for individuals' 
health and has been shown to correlate with perceived stress. For this 
data science challenge, we will be digging into the SWELL Knowledge Work 
dataset. Published in 2014, this dataset measures stress of individuals 
doing various knowledge work related tasks. Details of the dataset and 
some previous studies are outlined in the following three papers included
in this repository:


## Kizito et. al 2014

Abstract:

This paper describes the new multimodal SWELL knowl-
edge work (SWELL-KW) dataset for research on stress and
user modeling. The dataset was collected in an experiment,
in which 25 people performed typical knowledge work (writ-
ing reports, making presentations, reading e-mail, searching
for information). We manipulated their working conditions
with the stressors: email interruptions and time pressure.
A varied set of data was recorded: computer logging, facial
expression from camera recordings, body postures from a
Kinect 3D sensor and heart rate (variability) and skin con-
ductance from body sensors. The dataset made available not
only contains raw data, but also preprocessed data and ex-
tracted features. The participants’ subjective experience on
task load, mental effort, emotion and perceived stress was
assessed with validated questionnaires as a ground truth.
The resulting dataset on working behavior and affect is a
valuable contribution to several research fields, such as work
psychology, user modeling and context aware systems.


## Koldijk et. al 2018

Abstract:

Employees often report the experience of stress at work. In the SWELL project we investigate how new context aware
pervasive systems can support knowledge workers to diminish stress. The focus of this paper is on developing automatic classifiers to
infer working conditions and stress related mental states from a multimodal set of sensor data (computer logging, facial expressions,
posture and physiology). We address two methodological and applied machine learning challenges: 1) Detecting work stress using
several (physically) unobtrusive sensors, and 2) Taking into account individual differences. A comparison of several classification
approaches showed that, for our SWELL-KW dataset, neutral and stressful working conditions can be distinguished with 90 percent
accuracy by means of SVM. Posture yields most valuable information, followed by facial expressions. Furthermore, we found that
the subjective variable ‘mental effort’ can be better predicted from sensor data than, e.g., ‘perceived stress’. A comparison of several
regression approaches showed that mental effort can be predicted best by a decision tree (correlation of 0.82). Facial expressions
yield most valuable information, followed by posture. We find that especially for estimating mental states it makes sense to address
individual differences. When we train models on particular subgroups of similar users, (in almost all cases) a specialized model
performs equally well or better than a generic model.

## Kizito et. al 2019

Abstract:

Work stress and thermal discomfort are some of the hurdles that office workers face every day.
Office workers experience a periodic work stress because work is long and mentally challenging.
At the same time, current thermal comfort provision technologies are inefficient and consume a
large amount of energy. In our previous works, we proposed an efficient thermal comfort provision
system that is based on a person's heart rate variability (HRV). However, because work stress can
also affect the person's HRV, this paper investigates the possibility to distinguish HRV changes
that are due to thermal discomfort from changes that emanate from work stress. We conducted
experiments on subjects taking Advanced Trail Making Test (ATMT) and observed that stress
alters HRV and that it is possible to distinguish stressed and non-stressed subjects with a 100%
accuracy. We validated our method on the multimodal SWELL knowledge work (SWELL-KW)
stress dataset and achieved similar results (99.25% accuracy and 99.75% average recall). Further
analysis suggests that, although both thermal comfort and work stress affect HRV, their effect
is perhaps non-overlapping, and that the two can be distinguished with a near-perfect accuracy.
These results indicate that it could be possible to design an automatic and unobtrusive system
that delivers thermal comfort and predicts work stress based on people's HRV.
