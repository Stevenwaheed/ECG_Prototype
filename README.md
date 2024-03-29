# ECG_Prototype
This notebook use neurokit and heartpy packages to filter ECG waves and extract the main features from these waves.

## Dataset
In our prototype we use a dataset from Physionet website that has a lot of ecg datasets that can help us in our project.
We choose the ecg-id-database-1.0.0 to test our algorithms that used to filter this ecg waves and use features extraction algorithms to extract 30 main features that used in authentication systems.
Database contains 310 ECG recordings, obtained from 90 persons:
- each recording contain 20-second I-lead ECG signal;
- 10 beats in every recording are annotated (unaudited R- and T-wave peaks annotations from an automated detector);
- signals were digitized at 500 Hz with 12-bit resolution;
- number of records for each person vary from 2 (collected during one day) to 20 (collected periodically during 6 months);
- each recording is supplied with an information containing age, gender and record date;
- records were obtained from volunteers among students, colleagues and friends (44 men and 46 women aged from 13 to 75 years);

## Technologies
1- neurokit: used to exctract main features to distinguish between people.

2- heartpy: used to filter ECG waves and remove the noise.


## Formulas
1- Distance Formula:

![(21) Distance formula](https://github.com/Stevenwaheed/ECG_Prototype/assets/83607748/e4d5b286-12c4-4555-8e3a-53687610a588)


2- Slope Formula:

![(22) slope formula](https://github.com/Stevenwaheed/ECG_Prototype/assets/83607748/b68ce856-15b0-488b-991e-6dcdbd13bf06)


3- Amplitude Formula:

![Screenshot 2023-02-07 053641](https://github.com/Stevenwaheed/ECG_Prototype/assets/83607748/b59f116e-4e59-47c1-bc0a-1fea55bf48e9)


4- Interval Formula:

![Screenshot 2023-02-07 054021](https://github.com/Stevenwaheed/ECG_Prototype/assets/83607748/045ce254-a788-4bf7-a3f1-8bdd68be6fdb)





## Future work
we are looking for using the smartwatches to take the ECG waves and send them to these algorithms to build an authentication system.
