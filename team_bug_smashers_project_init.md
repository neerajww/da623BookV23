# Singing voice separation

## Team Name
BugSmashers

## Team Members
* Shelly Chouhan 	190101082 	CSE 	bachelors
* Kunal Maan 		190101047 	CSE 	bachelors
* Kshitij Arora 	190101046 	CSE 	bachelors

## Project Title
Singing voice separation from monaural recordings using Deep recurrent neural networks

## Background
Monaural source separation, separating individual sounds from a mixed audio recording, has many practical applications such as enhancement of accuracy in speech recognition and separating singing voice from music to improve accuracy of pitch estimation and chord recognition. However, current state-of-the-art methods are not as effective as human capability, and the problem is even more challenging since only single channel information is available. This problem focuses on singing voice separation from monaural recordings, and explores the use of deep recurrent neural networks(DRNNs) for this task, along with joint optimization of the network and a soft masking function.

## Methodology
* Waveform of a music(the mixture of voice and background music) is transformed to magnitude and phase spectra by Short-Time Fourier Transformation(STFT).
* Only magnitude spectra are processed as input of the RNN layer. Magnitude spectrum refers to the representation of the magnitude of the frequency components of a signal.
* The magnitude spectrum can be used to identify the frequency components of the singing voice and separate them from other sources of sound, such as background music or instruments. 
* Then we'll  use joint discriminative training, which is a technique used in machine learning to train models that can perform multiple related tasks simultaneously. In the context of singing voice separation from multiple sources using RNNs, joint discriminative training involves training the RNNs to jointly perform the task of separating the different singing voices while also optimizing their performance on other related tasks, such as noise reduction or reverberation removal.
* Estimated magnitude spectra of each sources and phase spectra of the mixture are transformed to waveform of each sources by ISTFT(inverse Short Time Fourier Transform).

## Deliverables
* A .py file that checks that the summation of resulting audio sources must match the input source.
* A GitHub repository containing the source code and documentation of the project
* An oral presentation in class

## Dataset to be used
For our experiments, we needed a dataset of songs with different attributes such as lyrics, rhythm, etc. After researching various datasets, we found the MIR-1k dataset, which was perfect for our needs. The MIR-1k dataset is a collection of one thousand songs sung by Chinese singers. It includes different genres of music, such as pop, rock, and classical, which allows us to test the performance of our proposed framework on various musical styles. Additionally, the dataset includes a wide range of vocal characteristics, such as male and female voices with different ranges, which makes it suitable for testing the robustness of our proposed framework on different singing voices. Overall, the MIR-1k dataset is an ideal resource for our research in monaural singing voice separation.

## References
* P.-S. Huang and S. D. Chen and P. Smaragdis and M. Hasegawa-Johnson, "Singing-voice separation from monaural recordings using robust principal component analysis" Proceedings of the IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)

* Colin Raffel, Brian McFee, Eric J. Humphrey, Justin Salamon, Oriol Nieto, Dawen Liang, and Daniel P. W. Ellis, "mir_eval: A Transparent Implementation of Common MIR Metrics", Proceedings of the 15th International Conference on Music Information Retrieval, 2014.

