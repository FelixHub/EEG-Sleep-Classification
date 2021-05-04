# EEG Sleep Classification

This the code I used for a Kaggle competition hosted by the [dreem](https://dreem.com/) startup.

The challenge was a multiclass classification of EEG headset signals, recorded over multiple nights on multiple subjects. We had to classify the data among different sleep stages (awake, stage 1, stage 2, stage 3, REM).

Feature extraction was a big part of the project, after which we used XGBoost to obtain an very high F1-score. 

An Hidden Markov Model was used to take advantage of the ordered structure of the unlabeled data.
