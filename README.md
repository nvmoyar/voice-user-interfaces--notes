# Automatic Speech Recognition Lab

## Motivation

This repo covers most of the math theory necessary to tackle the Voice User Interfaces Capstone project as part of the Artificial Intelligence Engineer Nanodegree VUI Concentration. 
You will find a lot of useful references, some recommended by Udacity and some other found along the way, within each notebook. 

A good starting point to put yourself in context can be [this video lecture from Apple](https://www.youtube.com/watch?v=PJ_KCTsOCrs) of Dr. Lee, suggested by Udacity.  

The motivation behind these notebooks is to introduce the first approach to implement these algorithms in Python, so you will find that some code is mixed with the notes and the maths. 

## Index

### [Basic Acoustics](Basic_Acoustics_from_Speech_to_Features_using_MFCC.ipynb)

This first notebook is an introduction to acoustics, and it is needed to understand the complexity of an acoustic signal, and the dimension of the problem we are facing in ASR. 

#### Concepts covered: 

* Speech signal
* Fourier Theory
* Spectrograms and FFT (+ intro to implementation)
* Feature extraction (Cepstra coeff)
    - Mel Scale + Math
    - Computation of Cepstrum

### [Automatic Speech Recognition](Automatic_Speech_Recognition_ASR.ipynb)(IN PROGRESS)

This notebook covers the main components of an ASR pipeline and explains component by component the problem, the task to be done and the math models behind. Most references for this notebook have been taken from [https://web.stanford.edu/~jurafsky/slp3/9.pdf] and this [https://web.stanford.edu/class/cs224s/lectures/224s.17.lec3.pdf], which are excellent references but quite long to process. 

#### Concepts covered: 

* Challenges in ASR
* Task Dimensions
* Pipeline
* Acoustic Model and Hidden Markov Models
* Language Model and n-Grams

### [HandsOn LibriSpeech Dataset Minilab](./AIND-VUI-Voice-Data--minilab/Lab_Voice_Data.ipynb)

This minilab comes from Udacity and is supposed to be a hands-on the VUI Capstone project. You may notice some difference with the original Udacity's Voice lab, since some of the quizzes from the Student Interface, and related to this problem, have been included here. 

The purpose of this lab is to gain familiarity with speech data you might use to train an Automatic Speech Recognition (ASR) system. For this problem, we will be using a subset of LibriSpeech dataset. 

#### Concepts covered: 

* Explore the LibriSpeech data set and format
* Create your own audio files
* Build your own audio data set


