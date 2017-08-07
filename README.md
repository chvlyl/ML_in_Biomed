# Machine Learning in Healthcare and Biomedical Applications

* Data driven decision making
* Questions -> Data -> Models/Tools

# Table of Contents
1. [Overview](#overview)
2. [EHR data](#ehr)
3. [Insurance claims data](#claims)
4. [Clinical notes](#clinicalnotes)
5. [Image data](#image-data)
6. [Time series data](#time-series-data)
7. [Genomics data](#genomics)




## Overview
|Data type|Models/Tools|Applications|
|---|---|---|
|-EHR data <br/>-Insurance claims data |ML(logistic regression,XGBoost)|Predict outcomes (disease, death, readmission etc.)|
|-Clinical notes <br/>-Conversation text data|-Rule based approach(regular expression)<br/>-Deep learning apporach|-Extrac concepts from clinical notes <br/>-Knowledge graphs<br/>-Chat-bot<br/>-QA system|
|Image data (X-ray, NMR, OCR image etc.)|CNN|-Detection: Diagnosis of skin cancer lung nodule or diabetic reinopathy<br/>-Segmentation of tumor, histopathology|
|Time series data (EEG, ECG, vital sign data etc.)|HMM,RNN,CNN|-Sleep disorder(apnea)<br/>-ICU monitoring|
|Genomics data|GATK,QIIME|-Cancer mutation identification<br/>-Biomarker identification<br/>-Durg discovery |
|Other data (hospital operational data)|-ML(regression)<br/>-Queueing model|-Reduce operatoinal cost<br/>-Improve patient experience<br/>-ER wait time and queueing|


## Image data


## Time series data
|Question|Models/Tools|Data|Sample|Reference|Year|
|---|---|---|---|---|---|
|sinus rhythm and atrial fibrillation|34-layer convolutional neural network (CNN)|single-lead ECG|-(Train) 64,121 ECG records
from 29,163 patients<br/>-(Test) 336 records from 328 unique
patients|[Cardiologist-Level Arrhythmia Detection with Convolutional Neural Networks](https://arxiv.org/abs/1707.01836)|2017|
