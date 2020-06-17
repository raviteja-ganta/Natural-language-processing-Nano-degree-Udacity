# Natural-language-processing-Nano-degree-Udacity
This repo contains all project files which are implemented as part of Natural language processing Nanodegree from Udacity in colloboration with Amazon alexa and IBM Watson

*Majority of projects in this repo make use of Tensorflow deep learning framework for training neural networks*

## Contents:

* [Part of Speech tagging](https://github.com/raviteja-ganta/Natural-language-processing-Nano-degree-Udacity/tree/master/Part%20of%20Speech%20Tagging) - Part of speech tagging is the process of determining the syntactic 
  category of a word from the words in its surrounding context. It is often used to help disambiguate natural 
  language phrases because it can be done quickly with high accuracy. Tagging can be used for many NLP tasks 
  like determining correct pronunciation during speech synthesis (for example, dis-count as a noun vs dis-count as a verb), 
  for information retrieval, and for word sense disambiguation. In this notebook, I used the Pomegranate library to build a hidden Markov model for part of speech tagging using a "universal" tagset. Hidden Markov models have been able to achieve >96% tag accuracy with larger tagsets on realistic text corpora. Hidden Markov models have also been used for speech recognition and speech generation, machine translation, gene recognition for bioinformatics, and human gesture recognition for computer vision, and more.

  Main steps involved are:
  1) Read and preprocess the dataset
  2) Build Most frequent class tagger amd make predictions with this model
  3) Build an HMM tagger
     1) Unigram counts
     2) Bigram counts
     3) Sequence starting counts
     4) Sequence ending counts
     5) Basic HMM tagger
   
* [NLP Machine translation](https://github.com/raviteja-ganta/Natural-language-processing-Nano-degree-Udacity/tree/master/NLP%20Machine%20translation) - Goal of this project is to build a deep neural network that functions as part of an end-to-end machine translation pipeline. Completed pipeline will accept English text as input and return the French translation.

  Main steps involved are:
  1) Preprocess input data
  2) Experiment with various models
     1) Simple RNN
     2) RNN with Embedding
     3) Bidirectional RNN
     4) Encoder-Decoder RNN
  3) Prediction

* [VUI Speech recognizer](https://github.com/raviteja-ganta/Natural-language-processing-Nano-degree-Udacity/tree/master/VUI%20Speech%20recognizer) - Goal is to build a deep neural network that functions as part of end-to-end automatic speech recognition (ASR) pipeline. This pipeline will accept raw audio as input and return a predicted transcription of the spoken language

  Main steps involved are:
  1) Pre-processing step that converts raw audio to one of two feature representations that are commonly used for ASR
  2) Deep Neural networks for Acoustic modelling
     1) Simple RNN
     2) RNN + TimeDistributed Dense
     3) CNN + RNN + TimeDistributed Dense
     4) Deeper RNN + TimeDistributed Dense
     5) Bidirectional RNN + TimeDistributed Dense
     6) Final model: CNN + dropout + Bidirectional RNN + TimeDistributed Dense
  3) Compare the models
  4) Obtain predictions
