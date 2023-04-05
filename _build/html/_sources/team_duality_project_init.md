# COPD Detection

## Team Name
Duality

## Team Members
* Rahul Bhardwaj, 226150002, PhD, MFSDSAI
* Prakhar Kumar Sonkar, 226150102, PhD, MFSDSAI

## Project Title
Detecting COPD Respiratory Diseases with Audio Recordings and Deep Learning

## Objective
The objective of this project is to develop an accurate and efficient system for detecting Chronic Obstructive Pulmonary Disease (COPD) using respiratory sound analysis with the help of deep learning techniques. The project aims to train a deep learning model on a large dataset of respiratory sound recordings to accurately classify patients with COPD and distinguish them from healthy individuals. The resulting model should provide a reliable and non-invasive method for early detection and diagnosis of COPD, which could potentially improve patient outcomes and reduce healthcare costs.

## Background
Chronic Obstructive Pulmonary Disease (COPD) is a chronic respiratory disease characterized by a progressive reduction in lung function, making it difficult to breathe. Early diagnosis and intervention can significantly improve patient outcomes and quality of life. Traditionally, COPD is diagnosed through spirometry, which is an invasive and time-consuming procedure.
Recent studies have shown that respiratory sound analysis can be a non-invasive and effective method for diagnosing COPD. Deep learning techniques have been applied to this field and have shown promising results. Deep learning algorithms can learn from large datasets of respiratory sound recordings, and can accurately classify COPD patients from healthy individuals.

## Methodology 
Detecting COPD from respiratory sounds involves analyzing the audio signals for abnormal patterns and characteristics that are indicative of the disease. Here's a general methodology for detecting COPD from respiratory sounds:
1.	Pre-process the respiratory sounds: In the pre-processing, we are trying to use data augmentation techniques such as pitch shifting, time stretching, and adding noise to make our model robust.
2.	Extract features from the respiratory sounds: Extract relevant features from the pre-processed respiratory sounds, these features can then be used to train a deep learning model to accurately detect COPD. We are trying to make a custom DNN which used to classify the five classes of COPD. 

## Deliverables
A .ipynb notebook detailing the preprocessing, feature extraction, and deep learning model to classify the five classes of COPD.
A GitHub repository containing the source code and documentation of the project.
An oral presentation in class.

## Dataset to be used
1.	ICBHI 2017 Challenge - Respiratory Sound Database- The database was created by two research teams in Portugal and in Greece, and it includes 920 recordings acquired from 126 subjects. A total of 6898 respiration cycles were recorded. The cycles were annotated by respiratory experts as including crackles, wheezes, a combination of them, or no adventitious respiratory sounds. 
2.	RespiratoryDatabase@TR (COPD Severity Analysis)

## References
1.	Rocha, B.M. et al. (2018). Α Respiratory Sound Database for the Development of Automated Classification. In: Maglaveras, N., Chouvarda, I., de Carvalho, P. (eds) Precision Medicine Powered by pHealth and Connected Health. ICBHI 2017. IFMBE Proceedings, vol 66. Springer, Singapore. https://doi.org/10.1007/978-981-10-7419-6_6
2.	I. Sen, M. Saraclar and Y. P. Kahya, "Differential Diagnosis of Asthma and COPD Based on Multivariate Pulmonary Sounds Analysis," in IEEE Transactions on Biomedical Engineering, vol. 68, no. 5, pp. 1601-1610, May 2021, doi: 10.1109/TBME.2021.3049288
3.	R. K. Tripathy, S. Dash, A. Rath, G. Panda and R. B. Pachori, "Automated Detection of Pulmonary Diseases From Lung Sound Signals Using Fixed-Boundary-Based Empirical Wavelet Transform," in IEEE Sensors Letters, vol. 6, no. 5, pp. 1-4, May 2022, Art no. 7001504, doi: 10.1109/LSENS.2022.3167121.







