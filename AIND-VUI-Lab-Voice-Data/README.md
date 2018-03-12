# AIND-VUI-Lab-Voice-Data

The purpose of this lab is to gain familiarity with speech data you might use to train an Automatic Speech Recognition (ASR) system. In the following steps, you'll:

* Explore the LibriSpeech data set and format
* Create your own audio files by installing Sonic Visualizer [https://www.sonicvisualiser.org]
* Build your own audio dataset

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