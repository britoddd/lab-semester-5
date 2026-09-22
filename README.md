# Lab Binus Semester 5 - 2026/2027
This repository is **currently on progress**, containing all codes of Deep Learning  & Speech Recognition Laborartory classes at BINUS University @Kemanggisan (BA01). You can freely use this code for learning or as references for these specific subjects.  :)  

## Getting Started 
This repository is split into two different classes: Deep Learning & Speech Recognition. Each class has different dependencies, so you have to install both of them.

## Deep Learning Setup
### 1. Python Installation
This whole code in this repository are run with **Python 3.10.9**  
#### Conda Installation
If you're using conda, you can create a new conda environment with conda:   
`conda create -n deep_learning python=3.10.9`  
#### Global Python Installation
Otherwise, you can manually install python on:  
https://www.python.org/downloads/release/python-3109/

### 2. Mandatory Python Libraries
It's highly recommended to create environment with the same version as listed below. If you used newer version of Python, the Tensorflow can't natively use the GPU Acceleration, which run slower because only be able to utilize CPU. Different version also can lead to error when compiling the program because some syntaxes are different between versions. All mandatory libraries has been listed below:
```
gymnasium==0.28.1
ipykernel==6.19.2
matplotlib==3.7.1
numpy==1.23.1
pandas==2.0.3
seaborn==0.12.2
scikit-learn==1.3.0
tensorflow==2.10.0
tensorflow-datasets==1.2.0
transformers==4.29.2
```
All the requirements above can be installed using Python package installer (pip):  
`pip install -r requirements.txt`

> **Extra note**: Tensorflow GPU acceleration only works on CUDA version 11.2, which is older version. This current setup doesn't work with newer version of NVIDIA GPU

## Speech Recognition Setup
This whole code in this repository are run with **Python 3.10.9**. It's recommended to use conda instead of vanilla python, you can create a new conda environment with conda:   
`conda env create -f environment.yml`  

All mandatory libraries has been listed below (conda will choose the best version itself):
```
python=3.10.9
pytorch
torchaudio
ipykernel
ipython
pysoundfile
librosa
pydub
```

## Direct Clone This Repository
If you want to download all the codes into your own local devices, you can run git with this command inside your  machine:   
`git clone https://github.com/britoddd/lab-semester-5.git`

## Contributor
**@britoddd** (Brian Nicholas)