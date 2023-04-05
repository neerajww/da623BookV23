# Epileptic Seizures

## Team Name
ICA 

## Team Members
* Umesh Kumar Naik M 226102024 ECE PhD

## Project Title
Comparison of various Machine Learning and Deep Learning approaches for the Classification of Epileptic Seizures From EEG Signals        

## Objective
The objective of this work is to compare and evaluate the performance of various machine learning and deep learning approaches for the classification of epileptic seizures from EEG signals. The aim is to identify the most effective method for accurately and efficiently classifying epileptic seizures, which could have important applications in clinical settings for diagnosing and treating epilepsy.

## Background
Epilepsy is a neurological disorder that affects approximately 50 million people worldwide. It is characterized by recurrent seizures, which are abnormal electrical activities in the brain. Electroencephalogram (EEG) signals are commonly used for the diagnosis and monitoring of epilepsy. Machine learning and deep learning approaches have shown promising results in the classification of epileptic seizures from EEG signals. In this study, we aim to compare various machine learning and deep learning approaches for the classification of epileptic seizures from EEG signals. We will evaluate the performance of these approaches using various metrics such as accuracy, sensitivity, specificity, and area under the curve (AUC). This work is important as accurate classification of epileptic seizures can aid in the diagnosis and treatment of epilepsy.

## Methodology
The methodology for this work involves the following steps:

* Data acquisition: EEG signals from patients with epilepsy and control are collected using standard clinical procedures.
* Preprocessing: The EEG signals are preprocessed and segmented into relevant frequency bands.
* Feature extraction: Various features are extracted from the preprocessed EEG signals to represent the underlying dynamics of the brain activity.
* Model selection: Several machine learning and deep learning models are evaluated for their performance in classifying epileptic seizures from EEG signals.
* Training and testing: The selected models are trained on a subset of the data and tested on a separate validation set to evaluate their accuracy and generalization performance.
* Performance evaluation: The performance of the models is evaluated using various metrics such as accuracy, sensitivity, specificity, and F1 score.
* Comparison and analysis: The results of the different models are compared and analyzed to identify the most effective approach for classifying epileptic seizures from EEG signals.


And the work is implemented in five different approaches:
- Handcrafted features + ML
    * TD, FD, TFD
    * Classification using ML models
- Dimension reduced features + ML
    * Dimensionality reduction of features using PCA
    * Decomposition using DWT and then
- 1D CNN
- Autoencoder (latent space representation)
- Spectrogram based 2D CNN

## Deliverables
* A GitHub repository containing the workflow and documentation of the project.
* An oral presentation in class.

## Dataset to be used
The dataset used in our work is taken from the publicly available database of department of epileptology from university of Bonn, Germany. The Dataset is comprised of five groups, namely A to E, each group contains 100 single-channel EEG signals, and each signal is of 23.6-sec in length with 4097 examples.

## References
1. bout Epilepsy | CDC. About Epilepsy | CDC, 30 Sept. 2020, www.cdc.gov/epilepsy/about/index.htm.
2. Vagus Nerve Stimulation - Mayo Clinic. Vagus Nerve Stimulation - Mayo Clinic, 17 Nov. 2020.
3. https://mikaelhaji.medium.com/a-technical-deep-dive-on-elon-musks-neuralink-in-40-mins-71e1100f54d4
4. Shensa, Mark J. "The discrete wavelet transform: wedding the a trous and Mallat algorithms." IEEE Transactions on signal processing 40.10 (1992): 2464-2482.
5. Abdi, Hervé, and Lynne J. Williams. "Principal component analysis." Wiley interdisciplinary reviews: computational statistics 2.4 (2010): 433-459.
