# Piano Music

## Team Name
Gamma

## Team Members
* Rishav Mondal 190101072 CSE bachelors
* Tanay Maheshwari 190101092 CSE bachelors
* Swapnil Srivastava 190101090 CSE bachelors 
* Raghav Gupta 190101069 CSE bachelors
* Nikhil Pandey 190123040 MnC bachelors
* Vikash Nirwan 190103121 Mechanical bachelors 


## Project Title
Generating Piano Music

## Objective
The objective of this project is to generate piano music for given initial set of seed notes. Our project would help musicians to create piano melodies automatically given initial few notes (say starting 50 notes).

## Background
Until now, creation of music has been seen as a profoundly human endeavour. As a result, researchers have been interested in learning whether creation of music can be truly automated or not. Such a fascination long predates notions such as *Turing test* (test to determine whether a machine can exhibit intelligent behaviour equivalent to that of a human), and has seen efforts to formalize and set strict rules of composition.  The use of rules exemplifies the algorithmic (and largely deterministic) approach to music generation, and this is what we wish to explore by means of this project. 

## Methodology
The approach consists of the following steps:
* Parse the dataset and choose only the initial 30 second/1 min of each audio clip in order to reduce training time.
* extract relevant information from midi files and converting it to 2D array format which we will feed to model.
* Use a ML model to learn melody :- currently considering RNN/GAN.
* Use loss function to update weights of the neural net.
* Output: Provide an initial note sequence (let's say 50) and the model will predict the next note to be played.

For **evaluation**, using objective measures like log likelihood may lead to misleading results, as stated in the reference paper. Thus, it turns out that manually listening to the generated music (preferably by experts), is the only way to judge it's quality. We also stick to music with no long term coherent structure, as it is difficult to learn such type of music with long melody sequences.

## Deliverables
* A GitHub repository containing RNN/GAN based code for our piano melody generating system, as well as documentation for our project.
* Comparison of different hyperparameter configurations of the RNN/GAN.
* Comparison with models proposed in reference work.
* An HTML page where generated audio can be easily played and quality of generated music can be easily evaluated.
* Final oral presentation and demonstration of our project.

## Dataset to be used
1. **MAESTRO** dataset compiled by Magenta.
    * The dataset contains about 200 hours of paired audio and MIDI recordings from ten years of International Piano-e-Competition.
    * Audio files are stored in MIDI format which we can use for preprocessing.
    * Because training on such a large dataset would be pretty time consuming, we decide to use only the initial 30 seconds or 1 minute of each piano melody.

## References
1. Oore, Simon, Dieleman, Eck, Simonyan (2018). This time with Feeling: Learning Expressive music performance ([arXiv:1808.03715](https://arxiv.org/abs/1808.03715) [cs.SD])