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
|Diabetic retinopathy|CNN|retinal fundus images|128175 retinal images|[Development and Validation of a Deep Learning Algorithm for Detection of Diabetic Retinopathy in Retinal Fundus Photographs](http://jamanetwork.com/journals/jama/fullarticle/2588763)|2016|
|Skin cancer |CNN|skin images|129,450 skin images|[Dermatologist-level classification of skin cancer with deep neural networks](https://www.nature.com/nature/journal/v542/n7639/full/nature21056.html)|2017|
|Tumor|CNN|Pathology images|400+110 slides|[Detecting Cancer Metastases on Gigapixel Pathology Images](https://arxiv.org/abs/1703.02442)|2017|


## Time series data
|Prediction outcomes|Models/Tools|Data type|Sample size|Reference|Year|
|---|---|---|---|---|---|
|sinus rhythm and atrial fibrillation|34-layer convolutional neural network (CNN)|single-lead ECG|-(Train) 64,121 ECG records from 29,163 patients<br/>-(Test) 336 records from 328 unique patients|[Cardiologist-Level Arrhythmia Detection with Convolutional Neural Networks](https://arxiv.org/abs/1707.01836)|2017|
|Hand movements|CNN|sEMG|67 intact subjects and 11 transradial amputees|[Deep Learning with Convolutional Neural Networks Applied to Electromyography Data: A Resource for the Classification of Movements for Prosthetic Hands](http://journal.frontiersin.org/article/10.3389/fnbot.2016.00009/full)|2016|
|Review||ICU data||[Machine Learning and Decision Support in Critical Care](http://ieeexplore.ieee.org/document/7390351/?part=1)|2017|



## Genomics data
|Prediction outcomes|Models/Tools|Data type|Sample size|Reference|Year|
|---|---|---|---|---|---|
|Genetic variants|Exome NGS|NGS&EHR data|50,726 individuals|[Distribution and clinical impact of functional variants in 50,726 whole-exome sequences from the DiscovEHR study](http://science.sciencemag.org/content/354/6319/aaf6814)|2016|
|Familial hypercholesterolemia|Exome NGS|NGS&EHR data|50,726 individuals|[Genetic identification of familial hypercholesterolemia within a single U.S. health care system](http://science.sciencemag.org/content/354/6319/aaf7000)|2016|


## Other
|Prediction outcomes|Models/Tools|Data type|Sample size|Reference|Year|
|---|---|---|---|---|---|
|Drug discovery|LSTM||12-27 assays|[Low data drug discovery with one-shot learning](http://pubs.acs.org/doi/full/10.1021/acscentsci.6b00367)|2017|
|Tutorial||Image||[Deep learning models for health care: challenges and solutions](http://www-bcf.usc.edu/~liu32/icml_tutorial.pdf)|2017|
|Tutorial||Image||[Deep learning in radiology: recent advances, challenges and future trends](https://ulasbagci.wordpress.com/2016/12/10/deep-learning-in-radiology-rsna-2016/)|2016|
|Tutorial||||[Big data analytics for healthcare](https://www.siam.org/meetings/sdm13/sun.pdf)|2013|
|Tutorial||Image||[Survey of deep learning in radiology](https://healthcare.ai/survey-of-deep-learning-in-radiology/)|2017|


