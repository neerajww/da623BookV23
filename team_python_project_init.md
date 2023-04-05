# Emotion Recognition

## Team Name
Python

## Team Members
* Adarsh Kumar 190101002 CSE B.Tech.
* Aryan Anshuman 190101013 CSE B.Tech.
* Hemant Wankhede 190101041	CSE B.Tech.
* Keshav Chourasiya	190101045 CSE B.Tech.
* Tanishq Katare 190101093 CSE B.Tech.
* Varenyam Bakshi 190101098	CSE B.Tech.

## Project Title
Emotion Recognition from EEG signals

## Objective
The objective of this project is to use DEAP EEG signals dataset to classify/recognize the emotions using CNN model and then check the performance of the model using various evaluation metrics like Accuracy, Specificity, Sensitiity, Confusion matrix.

## Background
EEG(electroencephalogram) signals are very efficient and painless technique to capture the time series of electrical activity of brain. EEG signals provide a direct measure of neural activity and reveals the underlying mechanisms of emotional processing and regulation. It is useful in diagnosing and treating psychiatric disorders improving human-robot interaction, enhancing virtual reality experiences. Signals captured from EEG can be decomposed into different frequency bands : alpha (8 - 13 Hz), beta (13 - 30 Hz), gamma (30 - 100 Hz), theta (4 - 8 Hz) and delta (1 - 4 Hz) using Fourier transforms. Emotion recognition and classification from EEG signals involves extracting relevant features to capture the dynamics of emotional responses across different brain regions and frequency bands. For classifying emotions we'll use CNNs. We are using CNNs because of ability of CNNs to automatically learn relevant features and classify complex patterns and can easily handle high-dimensional and noisy EEG data


## Methodology
One of the most widely accepted emotion model is the two-dimensional model 'Arousal-Valence'. We will be using the Open-Source DEAP dataset, which uses a similar emotion model but is an extended version. For starting with modelling the CNN we need to extract some features from the EEG signal first. We will be most probably using the spectrograms treated as images as the input to the CNN. We might do data augmentation for having diversifed training set for preventing cases of overfitting. After modelling we will assess the model using several evaluation metrics such as accuracy, specificity, sensitivity, f1-score and confusion matrix.
CNN model architecture can consist of multiple layers of convolutional layers, with activation functions such as rectified linear units (ReLU) or sigmoid functions. The hyperparameters such as filter size, stride, number of filters, dropout rate, and learning rate can be tuned to achieve better results. We haven't decided on specific parameters but will experiment on the go to achieve good results.


## Deliverables
* A .ipynb notebook implementing the idealogy of classification using CNN and assessing the performance on various ealuation metrics.
* A GitHub repository containing the source code and documentation of the project.
* An oral presentation in class.

## Dataset to be used
1.  A multimodal dataset for the analysis of human affective states. The electroencephalogram (EEG) and peripheral physiological signals of 32 participants were recorded as each watched 40 one-minute long excerpts of music videos. Participants rated each video in terms of the levels of arousal, valence, like/dislike, dominance and familiarity. For 22 of the 32 participants, frontal face video was also recorded. Most probably we will take 100 diverse datasets and train-test with 80-20 ratio while modelling.

## References
1. "DEAP: A Database for Emotion Analysis using Physiological Signals (PDF)", S. Koelstra, C. Muehl, M. Soleymani, J.-S. Lee, A. Yazdani, T. Ebrahimi, T. Pun, A. Nijholt, I. Patras, EEE Transactions on Affective Computing, vol. 3, no. 1, pp. 18-31, 2012
2. Mandhouj, Badreddine & Cherni, Mohamed & Sayadi, Mounir. (2021). An automated classification of EEG signals based on spectrogram and CNN for epilepsy diagnosis. Analog Integrated Circuits and Signal Processing. 108. 1-10. 10.1007/s10470-021-01805-2. 
3. H. Donmez and N. Ozkurt, "Emotion Classification from EEG Signals in Convolutional Neural Networks," 2019 Innovations in Intelligent Systems and Applications Conference (ASYU), Izmir, Turkey, 2019, pp. 1-6, doi: 10.1109/ASYU48272.2019.8946364.