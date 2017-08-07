# Machine Learning in Healthcare and Biomedical Applications

* Data driven decision making
* Questions -> Data -> Models/Tools

# Table of Contents
1. [Overview](#overview)
2. [EHR data](#ehr)
3. [Insurance claims data](#claims)
4. [Clinical notes](#clinicalnotes)
5. [Image data](#Image)
6. [Time series data](#time)
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
