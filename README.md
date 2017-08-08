# Machine Learning in Healthcare and Biomedical Applications

* Data driven decision making
* Questions -> Data -> Models/Tools

# Table of Contents
1. [Overview](#overview)
2. [EHR data](#ehr-data)
3. [Insurance claims data](#claims)
4. [Clinical notes](#clinical-notes)
5. [Image data](#image-data)
6. [Time series data](#time-series-data)
7. [Genomics data](#genomics-data)




## Overview
|Data type|Models/Tools|Applications|
|---|---|---|
|-EHR data <br/>-Insurance claims data |ML(logistic regression,XGBoost)|Predict outcomes (disease, death, readmission etc.)|
|-Clinical notes <br/>-Conversation text data|-Rule based approach(regular expression)<br/>-Deep learning apporach|-Extrac concepts from clinical notes <br/>-Knowledge graphs<br/>-Chat-bot<br/>-QA system|
|Image data (X-ray, NMR, OCR image etc.)|CNN|-Detection: Diagnosis of skin cancer lung nodule or diabetic reinopathy<br/>-Segmentation of tumor, histopathology|
|Time series data (EEG, ECG, vital sign data etc.)|HMM,RNN,CNN|-Heart disease<br/>-Sleep disorder(apnea)<br/>-ICU monitoring|
|Genomics data|GATK,QIIME|-Cancer mutation identification<br/>-Biomarker identification<br/>-Durg discovery |
|Other data (hospital operational data)|-ML(regression)<br/>-Queueing model|-Reduce operatoinal cost<br/>-Improve patient experience<br/>-ER wait time and queueing|

## EHR data


|Prediction outcomes|Models/Tools|Data type|Sample size|Reference|Year|
|---|---|---|---|---|---|
|Review||||[Mining electronic health records: towards better research applications and clinical care](https://www.nature.com/nrg/journal/v13/n6/full/nrg3208.html)|2012|
|Review||||[Opportunities and challenges in developing risk prediction models with electronic health records data: a systematic review](https://academic.oup.com/jamia/article/24/1/198/2631444/Opportunities-and-challenges-in-developing-risk)|2016|
|heart failure|-logistic regression<br/>-random forest|longitudinal EHR data|1684 heart failure cases and 13525 matched controls|[Early Detection of Heart Failure Using Electronic Health Records](http://circoutcomes.ahajournals.org/content/9/6/649.long)|2016|
|heart failure (review)||||[Population Risk Prediction Models for Incident Heart Failure](http://circheartfailure.ahajournals.org/content/8/3/438.long)|2015|
|Kidney transplant graft failure|Cox regression|10-years EHR data|69,440 kidney transpants|[A comprehensive risk quantification score for deceased donor kidneys: the kidney donor risk index](https://insights.ovid.com/pubmed?pmid=19623019)|2009|


## Clinical notes
|Prediction outcomes|Models/Tools|Data type|Sample size|Reference|Year|
|---|---|---|---|---|---|
|Review||||[Realizing the full potential of electronic health records: the role of natural language processing](https://academic.oup.com/jamia/article-lookup/doi/10.1136/amiajnl-2011-000501)|2011|
|Review||||[Natural language processing: an introduction](https://academic.oup.com/jamia/article-lookup/doi/10.1136/amiajnl-2011-000464)|2011|
|Negation|Regular expression and rule-based approach|Clinical reports|2060 discharge summaries|[A simple algorithm for identifying negated findings and diseases in discharge summaries](http://www.sciencedirect.com/science/article/pii/S1532046401910299?via%3Dihub)|2001|

## Image data
|Prediction outcomes|Models/Tools|Data type|Sample size|Reference|Year|
|---|---|---|---|---|---|
|Diabetic retinopathy|CNN|retinal fundus images|128175 retinal images|[evelopment and Validation of a Deep Learning Algorithm for Detection of Diabetic Retinopathy in Retinal Fundus Photographs](http://jamanetwork.com/journals/jama/fullarticle/2588763)|2016|



## Time series data
|Prediction outcomes|Models/Tools|Data type|Sample size|Reference|Year|
|---|---|---|---|---|---|
|sinus rhythm and atrial fibrillation|34-layer convolutional neural network (CNN)|single-lead ECG|-(Train) 64,121 ECG records from 29,163 patients<br/>-(Test) 336 records from 328 unique patients|[Cardiologist-Level Arrhythmia Detection with Convolutional Neural Networks](https://arxiv.org/abs/1707.01836)|2017|


## Genomics data
