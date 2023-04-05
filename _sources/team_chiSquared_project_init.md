# Rotating shaft analysis

## Team Name
Chisquad

## Team Members
* Sarthak Bhagwat 190103087 B.Tech
* Gyanendra Prakash 190103110 B.Tech
* Shubham Panchal 190103094 B.Tech
* MD SHAMS REZA 190103056 B.Tech

## Project Title
Machine learning based unbalance detection of a rotating shaft using vibration data.

## Objective
The objective of this project is to detect faults in rotating machinery with the help of vibration sensors offer the possibility to detect damage to machines at an early stage and prevent production downtimes by taking appropriate measures. The analysis of the vibration data using methods of machine learning promises a significant reduction in the associated analysis effort and a further improvement in diagnostic accuracy.

## Background
Progress in the field of machine learning has led to impressive results in recent years, these algorithms offer great potential for industrial applications. The analysis of vibrations on rotating shafts to detect unbalances or to detect damage to roller bearings has proven to be very promising. Unbalances on rotating shafts can cause decreased lifetimes of bearings or other parts of the machinery and, therefore, lead to additional costs. Hence, early detection of unbalances helps to minimize maintenance expenses, avoid unnecessary production stops, and to increase the service life of machines.

## Methodology
The methodology would involve use of FFT for feature extraction. We have sensors recording the vibrations due to unbalance in a rotating shaft. More precisely: unbalances of various sizes were attached to a rotating shaft using a 3Dprinted holder. In a speed range from approx. 630 RPM to
2330 RPM, three sensors were used to record vibrations on the
rotating shaft at a sampling rate of 4096 values per second. Fourier coefficients would be calculated and then scaled. . Fully
connected (FC) neural networks would then be trained on the
training data.

## Deliverables
* A .ipynb notebook detailing the variability analysis of handwritten signatures and the development of the signature verification system.
* A GitHub repository containing the source code and documentation of the project.
* An oral presentation in class.

## Dataset to be used
1. The above link contains the dataset, this dataset was recorded on a rotating drivetrain. This drivetrain consists of an electronically commutated DC motor and a shaft driven by it, which passed through a roller bearing.
[Link for dataset] (https://fordatis.fraunhofer.de/handle/fordatis/151.2) 

## References
1. Engin, D., Kantarci, A., Arslan, S., & Ekenel, H. K. (2020). Machine Learning-Based Unbalance Detection of a Rotating Shaft Using Vibration Data Oliver Mey; Willi Neudeck; André Schneider; Olaf Enge-Rosenblatt.
2. Aske Lorenz, Bende Siewertsen, Victor Kyhe Clemmensen, Josephine Blaamann Petersen, Jonas Friederich, Sanja Lazarova-Molnar, "Vibration Data Analysis for Fault Detection in Manufacturing Systems - A Systematic Literature Review", 2022 IEEE 17th Conference on Industrial Electronics and Applications (ICIEA), pp.851-857, 2022.
