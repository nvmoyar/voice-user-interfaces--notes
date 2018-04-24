# AIND-VUI-Lab-Voice-Data

The purpose of this lab is to gain familiarity with speech data you might use to train an Automatic Speech Recognition (ASR) system. In the following steps, you'll:

* Explore the LibriSpeech corpus and format
* Create your own audio files by installing Sonic Visualizer [https://www.sonicvisualiser.org]
* Build your own audio dataset

This is a very quick and funny lab which helps to understand why the data needs to be preprocessed and how is it done for the VUI Capstone project. 

By the end of this notebook, you will have an idea of how to build your own corpus for training an acoustic model. 


### Tasks to complete: 

* [Clone repo](https://github.com/udacity/AIND-VUI-Lab-Voice-Data). Please note that the Jupyter Notebook is not part of the original set of files provided by Udacity.
* Visit the LibriSpeech dataset website
* Complete the LibriSpeech Corpus Quizz (Udacity's brief questions about the dataset structure)
* Complete LibriSpeech Data Quiz
* Install Sonic Visualizer
* Create five .wav file about a sentence each -your voice recorded-
* View spectrogram of your audio
* Create dataset: STEP1 convert and structure
* Create a dataset: STEP2 Add utterances
* Create a dataset: STEP3 Create the json needed for processing

## Requirements

name: aind
channels:
- anaconda
- defaults
dependencies:
- matplotlib=2.1.1
- jupyter=1.0.0
- nb_conda=2.2*
- pandas=0.22.0
- python=3.5.4
- scikit-learn=0.19.1
- scipy=1.0.0
- tqdm=4.19.4
- pip:
  - hmmlearn==0.2.0
  - udacity-pa>=0.2
  - z3-solver
  - pip install pysoundfile 