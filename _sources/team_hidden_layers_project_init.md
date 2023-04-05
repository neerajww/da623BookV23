# Gravitational Wave

## Team Name
Hiddenlayers

## Team Members
* AnjaliPriya (190101012)
* Nancy (190101057)
* Sanidhya Patel (190101059)
* Adari Yashwanth (190104005)
* Bodele Gaurav Jayant (190101027)
* Shrey Verma (190101083)

## Project Title
Gravitational Wave Detection

## Objective
To build a model to analyze simulated GW time-series data
from a network of Earth-based detectors.

## Background
Einstein predicted that something special happens when
two bodies- such as planets or stars-orbit each other. He believed that
this kind of movement could cause ripples in space. These ripples would
spread out like the ripples in a pond when a stone is tossed in.
Scientists call these invisible ripples of space gravitational waves.

## Methodology
We will use the dataset provided by the LIGO from three
different sites to train and test the model. Before applying DFT we will
apply the window function like Tuckey Window to avoid spectral leakage.
Then will apply DFT to analyze and differentiate patterns between noise
and gravitational waves. Bandpass Filter will be applied to remove
low-frequency noise as well as down weighting of the frequency having
loud noise using whitening.

When GW was observed, Strain vs Time graphs were plotted. Numerical
relativity waveforms and reconstructed wavelets and templates can be
obtained with parameters consistent with observed data. If the signal
contains GW then the theoretical waveform overlaps the observed signal
with greater similarity. The model classifies the sample whether or not
it contains GW based on observing similar patterns between waveforms
obtained at different workstations. The sample can be classified as
containing GW if the three waveforms have similar patterns containing
lots of overlapping.

To identify gravitational waves, we will use preprocessed data to train
machine-learning models. The performance of the model will be evaluated
using the AUC-ROC score. We will compare the performance of our model
with recent methods used in literature and in different competitions
such as Kaggle.

## Deliverables
- A .ipynb notebook containing data analysis, data preprocessing and
different methods to identify gravitational waves.
- An oral presentation in class.

## Dataset
The training dataset: consists of Time series data
containing simulated gravitational wave measurements from a network of 3
gravitational wave interferometers. Each data sample contains 3-time
series which is either detector noise or detector noise plus a simulated
gravitational wave signal and each spans 2 sec and is sampled at 2,048
Hz. Different gravitational parameters (15 in total) have been
randomized according to astrophysically motivated prior distributions
and used to generate the simulated signals present in the data. Here
labels are provided (Target=1 means GW is present in the sample).
Samples are equally distributed (Equal number of samples with target=1
and target=0).

Testing dataset: consists of similar Time series data. The task is to
predict the probability that the observation contains a gravitational
wave.

## References
- B. P. Abbott et al.(2016) Observation of Gravitational Waves from a Binary Black Hole Merger; M. Bailes et al. (2021) Gravitational-wave physics and astronomy in the 2020s and 2030s.
- L. Ju et al (2000) Detection of gravitational waves.
