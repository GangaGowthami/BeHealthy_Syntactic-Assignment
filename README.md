# Identifying Entities in Healthcare Data
## Introduction
A health tech company called ‘BeHealthy’. They aim to connect the medical communities with millions of patients across the country. BeHealthy has a web platform that allows doctors to list their services and manage patient interactions and provides services for patients such as booking interactions with doctors and ordering medicines online. Here, doctors can easily organise appointments, track past medical records and provide e-prescriptions.

# Problem Statement
BeHealthy require predictive model which can identify disease and treatment from the patients interaction with doctor or ordering medicines online.

# Dataset Explanation
We have four data file for this activity to proceed, they are
- Train Sentence Dataset
- Train Label Dataset
- Test Sentence Dataset
- Test Label Dataset

Sentence file contains all iterations between patients and doctor and Label file contains all entity tags for particular words arranged as per sentence. We need to do few preprocessing while accessing dataset we will explore that in further steps.

# Library Explanation
- Pandas - Dataframe, Content storage and processing
- Regular Expression (re) - Identify the textual pattern
- SpaCy - NLP, POS tag check
- Warnings - To avoid warning messages
- Sklearn_CRFsuite - Model building and Evaluation

# Results
We now use the CRF model's prediction to prepare a record of diseases identified in the corpus and treatments used for the diseases.
Predicting the treatment for the disease name: 'hereditary retinoblastoma'
- Treatment for 'hereditary retinoblastoma' is 'radiotherapy'
- 
# Contact
Created by [@GowthamiGanga] - feel free to contact me!
