# <center>NeuraHealth: An Automated Screening Pipeline to Detect Undiagnosed Cognitive Impairment in Electronic Health Records using Deep Learning and Natural Language Processing</center>

## Author
Tanish Tyagi

## Abstract
Dementia-related Cognitive Impairment (CI) is a neurodegenerative disorder, affecting over 55 million people worldwide and growing rapidly at the rate of one new case every three seconds. The World Health Organization has established early detection as a principal goal for optimal management of CI. However, up to 90% of cases go undetected globally, costing USD 1.3 trillion annually and estimated to reach 2.8 trillion by 2030. With no cure, a recurring failure of clinical trials, and lack of early diagnosis, the mortality rate is 100%. Information in Electronic Health Records (EHR) provides vital clues for early diagnosis, but a manual review by experts is tedious and error-prone. This project presents an automated and scalable EHR screening pipeline, NeuraHealth, capable of diagnosing CI in EHR using deep learning and natural language processing. NeuraHealth consists of two novel components: a bi-directional attention-based model trained to diagnose CI and a two-step framework for disease diagnosis in EHR. Using patient EHR from Mass General Brigham, relevant sequences were extracted, classified, and used as features for a patient-level regularized logistic regression model. The diagnostic models outperformed all existing state-of-the-art computational and clinical methods by 15% due to enhanced understanding of linguistic context in complex language structures of EHR. Further, the models were integrated into a web application to make early diagnosis accessible in medical facilities, regions with scarce health services, and primary care centers. NeuraHealth has the potential to also be effectively applied to detect other chronic diseases in EHR like sleep apnea and diabetes.

## Navigating the Codebase
1. ```Models/``` - Houses all the code for the Machine Learning TFIDF, Deep Learning BERT models, and Patient Level Aggregration Model
2. ```Preprocessing/``` - Houses the code for the EHR Preprocessing Pipeline 
3. ```NeuraHealth-WebApp/``` - Houses all the code for the NeuraHealth web app

Each folder will also contain a ```README.md``` file that goes into further detail regarding its contents. 

**Note**: 
1. All folders named "Old" house code that was created during previous iterations of the project. All files in these folders are not relevant to the material discussed in the paper and do not need to be examined. Thank you!
2. Unless otherwise stated, all the code in the attached files is written by me. I use Import statements to call functions from external libraries.
