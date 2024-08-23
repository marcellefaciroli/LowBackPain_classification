# Classification of Low Back Pain using a Support Vector Machine model

Low back pain (LBP) is a widespread issue affecting a substantial segment of the global population. It can vary from minor discomfort to intense pain, with some instances involving nerve compression that leads to more severe symptoms. Effective treatment planning relies on precise diagnosis and classification of LBP, particularly in distinguishing between general low back pain and cases involving neural compression.

In recent times, machine learning (ML) and artificial intelligence (AI) have become transformative tools in healthcare, providing innovative methods for enhancing diagnosis and patient management. Among the various ML techniques, Support Vector Machines (SVM) are particularly effective for binary classification tasks. This makes SVM a valuable tool for differentiating between types of LBP. Using the Support Vector Classification (SVC) feature from the scikit-learn library, the model is designed to classify cases into general LBP or LBP with neural compression (LBPNC) based on a dataset from 168 patients. This dataset includes responses from an online survey that collects both demographic and clinical data, providing a detailed perspective on factors related to their condition.

Using various data preprocessing techniques, such as normalization and dummification, along with Fisher's Exact Test for feature selection and optimizing the model through grid search, this work aims to achieve accurate classification of LBP. The use of AI in this setting is intended not only to improve diagnostic accuracy but also to help healthcare providers identify patients at risk for more severe complications, such as neural compression. By integrating these technological advancements into clinical practice, the goal is to refine treatment approaches, lessen the impact of LBP on both individuals and healthcare systems, and enhance overall patient outcomes.

## Dependencies 
* pandas
* numpy
* scipy.stats
* matplotlib
* sklearn

## Files Overview

* main_complete.ipynb
  
This file contains all the data preprocessing, model optimization, and results without feature selection.

* main_fisher.ipynb
  
This file contains all the data preprocessing, feature selection using Fisher's Exact Test, model optimization, and final results.

## Dataset

If you wish to access the complete dataset used in this work, please contact the orthopedist Dr. Jair Moreira Dias Jr., who is responsible for selecting the patients who took part in the survey. 
E-mail: jairdias2@gmail.com
