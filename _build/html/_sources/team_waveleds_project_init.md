# Parkinson Diagnosis

## Team Name
WaveLeds

## Team Members
- Dheeraj_Nahar, 190103035, Mechanical_Engineering, bachelors
- Harshvardhan Singh, 190102101, ECE, bachelors
- Rahul Aggarwal, 190103120, Mechanical Engineering, bachelors
- Saksham Jain, 190107085, Chemical_Engineering, bachelors
- Simran Garg, 190101086, CSE, bachelors
- Soumya Gupta, 190101087, CSE, bachelors

## Project Title
Early Diagnosis of Parkinson's Disease

## Objective
The objective of this project is to detect the early onset of Parkinson's disease using deep learning and signal processing techniques.

## Background
Parkinson's disease (PD) is one of the most common movement disorders, affecting approximately 1 million Americans (estimates range between 4 and 6.5 million people worldwide) and about 1% of older adults. In the US alone, 60,000 new cases are diagnosed each year. PD is a chronic and progressive neurological disorder that results in tremor, rigidity, slowness, and postural instability.
There is no early diagnosis technique available for PD, and is only diagosed when the symptoms are visible to the naked eye making it too late to be cured.
By analyzing the gait data using signal processing methods, we can extract meaningful features and patterns that can aid in early diagnosis of Parkinson's Disease and even help us perform a severity analysis.

## Methodology
We will use a publicly available 'Gait in Parkinson's Disease' dataset on physionet to train and test our model. We will first perform noise reduction on our data using known techniques. Since our data consists signals from 8 sensors from each foot, we would first try to find correaltion between these 16 signals. If we donot find corellation between these signals, we would perform dimensionality reduction using known techniques such as PCA.

To develop a binary classification model, we will use the features to train a machine learning model. The paper that we are following used CNN model and gave good results[1]. We would start with a CNN model and try different deep learning models to increase the model performance. We will compare the performance of our model with recent methods in the literature ([2])

## Deliverables

- A .ipynb notebook denoting the correlation between the 16 signals from gait data.
- A .ipynb notebook denoting results for different sampling frequencies of the gait data.
- A .ipynb notebook containing the binary classification results.
- A GitHub repository containing the source code and documentation of the project.
- An oral presentation in class.

## Dataset to be used

1. Gait in Parkinson's Disease: This database contains measures of gait from 93 patients with idiopathic PD (mean age: 66.3 years; 63% men), and 73 healthy controls (mean age: 66.3 years; 55% men). The database includes the vertical ground reaction force records of subjects as they walked at their usual, self-selected pace for approximately 2 minutes on level ground. Underneath each foot were 8 sensors (Ultraflex Computer Dyno Graphy, Infotronic Inc.) that measure force (in Newtons) as a function of time. The output of each of these 16 sensors has been digitized and recorded at 100 samples per second, and the records also include two signals that reflect the sum of the 8 sensor outputs for each foot.

## References

1. Julia Camps, Albert Sama Monsonis, Mario Martin, Daniel Rodr´ıguez-Mart´ın, Carlos P´erez, Joan Arostegui, Joan Cabestany, Andreu Catal`a, Sheila Alcaine, Berta Mestre, Anna Prats, Maria Cruz Crespo Maraver, Timothy Counihan, Patrick Browne, Leo Quinlan, Gear´oid OLaighin, Dean Sweeney, Hadas Lewy, Gabriel Vainstein, and Alejandro Rodr´ıguez-Molinero. Deep learning for freezing of gait detection in parkinson’s disease patients in their homes using a waist-worn inertial measurement unit. Knowledge-Based Systems, 139, 10 2017.
2. Goldberger, A., Amaral, L., Glass, L., Hausdorff, J., Ivanov, P. C., Mark, R., ... & Stanley, H. E. (2000). PhysioBank, PhysioToolkit, and PhysioNet: Components of a new research resource for complex physiologic signals. Circulation [Online]. 101 (23), pp. e215–e220.
