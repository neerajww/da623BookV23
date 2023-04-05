# Voice Analytics

## Team Name
Bandwidth 

## Team Members
* Suryansh Singh 190101089 CSE Bachelors 
* Anant Shankhdhar 190101011 CSE Bachelors 
* Yashwardhan Modi 190101101 CSE Bachelors

## Project Title
Voice Analytics Toolkit

## Objective
The objective of this project is to explore the domain of machine learning and deep learning for the task of automatic speech recognition, this involves extracting features from speech data and then applying various deeplearning techniques to get the text out of speech data. We will also compare the performance, by varying sampling rate and bit rate of data. We will finally carry out sentiment analysis on the text obtained and provide an api for the same.

## Background 
Automatic Speech Recognition (ASR) is a technology that enables machines to understand and interpret human speech. It uses algorithms to convert spoken language into written text, which can then be analyzed or used to perform a variety of tasks, such as controlling devices or responding to user requests.
Sentiment analysis, also known as opinion mining, is a subfield of natural language processing (NLP) that focuses on identifying and extracting subjective information from text. The goal of sentiment analysis is to determine the sentiment or emotion expressed in a piece of text, whether it's positive, negative, or neutral.
Recent advancements in deep learning and neural networks have led to significant improvements in the accuracy and efficiency of sentiment analysis algorithms. Combined with ASR, sentiment analysis can be applied to analyze spoken language, providing valuable insights into customer sentiment and feedback in real-time.

## Methodology 
Automatic Speech Recognition: We plan on using DL models for speech recognition.
  * DeepSpeech -  It is a multi layer BiLSTM model which utilizes the CTC loss. We will train the model on Common Voice Dataset made available by the   Mozilla Foundation.
  * Wav2Vec2 - It is the state of the art transformer based model released by Facebook. Pretrained model is available which can also be used

## Experiments with ASR
* Evaluating performance of state-of-the-art ASR model with different:- 
  * Sampling Rates :- In speech recognition, sampling rate refers to the number of times per second that a speech signal is sampled and converted into a digital representation.
  * Bitrate :- Bitrate in speech recognition refers to the number of bits used to encode or represent each sample of a speech signal.
* Performance metrics:-
  * Word Error Rate :-  the number of insertions, deletions, and substitutions for words made by the ASR system. (It deals in words)
  * Levenshtein Distance :- is a metric used to measure the difference between two strings of characters. It calculates the minimum number of insertions, deletions, and substitutions needed to transform one string into the other. (It deals in charaters)

## Deliverables
* An .ipynb notebook containing a detailed analysis, graphs and comparison between models trained using different parametes.
* A GitHub repository containing the source code and documentation of the project.
* An oral presentation in class. * An spi that performs analysis of audio data on command

## Dataset to be used
1. Common Voice is a large, public dataset of voice recordings and their transcriptions, created and maintained by Mozilla, the non-profit organization behind the Firefox web browser. The dataset is intended to be used for research and development of Automatic Speech Recognition (ASR) systems.

The Common Voice dataset includes recordings of people speaking in various languages, accents, and dialects. The recordings are collected through a web-based platform, where volunteers can contribute their voice by reading sentences aloud. The sentences are chosen at random from a collection of prompts, which ensures that the dataset is diverse and representative of different types of speech.

The dataset is available for 96 languages but we will use the English split.


## References
1. Alexei Baevski, Henry Zhou, Abdelrahman Mohamed, & Michael Auli. (2020). wav2vec 2.0: A Framework for Self-Supervised Learning of Speech Representations.
2. Awni Hannun, Carl Case, Jared Casper, Bryan Catanzaro, Greg Diamos, Erich Elsen, Ryan Prenger, Sanjeev Satheesh, Shubho Sengupta, Adam Coates, & Andrew Y. Ng. (2014). Deep Speech: Scaling up end-to-end speech recognition.
3. Rosana Ardila, Megan Branson, Kelly Davis, Michael Henretty, Michael Kohler, Josh Meyer, Reuben Morais, Lindsay Saunders, Francis M. Tyers, & Gregor Weber. (2020). Common Voice: A Massively-Multilingual Speech Corpus.