# Natural-language-processing-Nano-degree-Udacity
This repo contains all project files which are implemented as part of Natural language processing Nanodegree from Udacity in colloboration with Amazon alexa and IBM Watson

*Majority of projects in this repo make use of Tensorflow deep learning framework for training neural networks*

## Contents:

* [Part of Speech tagging](https://github.com/raviteja-ganta/Natural-language-processing-Nano-degree-Udacity
/tree/master/Part%20of%20Speech%20Tagging) - Part of speech tagging is the process of determining the syntactic 
category of a word from the words in its surrounding context. It is often used to help disambiguate natural 
language phrases because it can be done quickly with high accuracy. Tagging can be used for many NLP tasks 
like determining correct pronunciation during speech synthesis (for example, dis-count as a noun vs dis-count as a verb), 
for information retrieval, and for word sense disambiguation.

In this notebook, you'll use the Pomegranate library to build a hidden Markov model for part of speech tagging using a "universal" tagset. Hidden Markov models have been able to achieve >96% tag accuracy with larger tagsets on realistic text corpora. Hidden Markov models have also been used for speech recognition and speech generation, machine translation, gene recognition for bioinformatics, and human gesture recognition for computer vision, and more.

* [Dog breed classifier using CNN's](https://github.com/raviteja-ganta/Deep-Learning-Engineer-Nano-degree-Udacity/tree/master/Dog%20breed%20classifier%20using%20CNN's) - Goal of this project is to use CNN to classify an image in to 133 breeds of dogs. My code will accept any user-supplied image as input. If a dog is detected in the image, it will provide an estimate of dog's breed. If a human is detected, it will provide an estimate of the dog breed that is most resembling.

  Main steps involved are:
  1) Detect Humans
  2) Detect Dogs
  3) Create a CNN to Classify Dog Breeds from scratch
  4) Create a CNN to Classify Dog Breeds(using Transfer Learning)
  5) Write final algorithm

* [Face generation using GAN's](https://github.com/raviteja-ganta/Deep-Learning-Engineer-Nano-degree-Udacity/tree/master/Face%20generation%20using%20GAN's) - Goal is to define and train DCGAN network on dataset of faces and finally to get our network generate new faces that look as realistic as possible.

  Main steps involved are:
  1) Define Discriminator network
  2) Define Generator network
  3) Initialize weights of above networks
  4) Build complete network using both discriminator and generator networks
  5) Calculate discriminator and generator losses
  6) Training the network

* [Generate TV Scripts](https://github.com/raviteja-ganta/Deep-Learning-Engineer-Nano-degree-Udacity/tree/master/Generate%20TV%20Scripts) - Goal is to generate Seinfeld TV scripts using RNNs. Neural network will generate a new, fake TV script, based on patterns it recognizes in this training data.

  Main steps involved are:
  1) Data Pre-processing and creating dataloader
  2) Build Neural network
  3) Define forward and backpropagation
  4) Selecting best hyperparameters
  5) Neural network training
  6) Generate TV Script 

* [Predicting Bike-Sharing Patterns](https://github.com/raviteja-ganta/Deep-Learning-Engineer-Nano-degree-Udacity/tree/master/Predicting%20Bike-Sharing%20Patterns) - Goal is to build simple deep neural network to predict daily bike rental ridership using numpy and pandas. This project doesnot make use of Pytorch as main goal is to understand forward and backpropagation logic
