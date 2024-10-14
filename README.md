# Master Thesis Project: Speech Recognition using Deep Learning

This repository contains the code and experiments for my master thesis, which focused on applying Deep Learning techniques to the field of Speech Recognition. The main objective of the research was to analyze audio timeseries data and develop a robust voice command recognition system using Neural Network models, specifically targeting two datasets: one derived from Greek dialogues and the other from English voice commands.

## Project Overview

The research tackled the problem of voice command recognition using three different approaches, implemented with Convolutional Neural Networks (CNNs) and Long Short-Term Memory (LSTM) networks.

### Experiment 1: Voice Command Classification with CNNs
In the first experiment, a CNN-based model was designed to classify voice commands from the Greek and English datasets. Special attention was given to handling the imbalanced distribution in the Greek dataset using data augmentation techniques to ensure reliable performance.

### Experiment 2: Speech-to-Text Transcription using CNNs and LSTMs
The second experiment aimed at building a speech-to-text system. A hybrid CNN-LSTM architecture was employed using Connectionist Temporal Classification to align spoken language with individual letters, enabling transcription of the voice commands into text.

### Experiment 3: Voice Command Similarity Search and Indexing
In the third and final experiment, the CNN structure from the first experiment was extended to implement a voice command similarity search using cosine similarity metric. This approach allowed efficient retrieval and comparison of similar voice commands.

## Code

- **1st_experiment.ipynb** includes the implementation of a voice command classifier for both datasets
- **1st_experiment(greek data augmentation).ipynb** includes the implementation of a voice command classifier using data augmentation techniques, in order to improve classification accuracy for the greek dataset.
- **2nd_experiment.ipynb** includes the implementation of an automatic speech recognition model using Connectionist Temporal Classification for both datasets
- **3rd_experiment.ipynb** includes the implementation of a similarity recognition and indexing of voice commands for both datasets

## Results
From these three experiments, three reliable systems were developed, all capable of recognizing spoken voice commands with high accuracy. The models demonstrated strong potential for future applications in automatic speech recognition and voice-activated systems.
