# Lab Binus Semester 5 - 2026/2027
This repository is **currently on progress**, containing all codes of Deep Learning  & Speech Recognition Laborartory classes at BINUS University @Kemanggisan (BA01). You can freely use this code for learning or as references for these specific subjects :)  

*Last updated:* ***September 8th, 2026***

## Getting Started
### 1. Required Python Version
This whole code in this repository are run with **Python 3.10.9**  
#### Conda Installation
If you're using conda, you can create a new conda environment with conda:   
`conda create -n lab_semester_5 python=3.10.9`  
#### Global Python Installation
Otherwise, you can manually install python on:  
https://www.python.org/downloads/release/python-3109/

### 2. Mandatory Python Libraries
It's highly recommended to create environment with the same version as listed below. If you used newer version of Python, the Tensorflow can't natively use the GPU Acceleration, which run slower because of CPU only utilization. Different version also can lead to error when compiling the program because some syntaxes are different between versions. All mandatory libraries has been listed below:
```
gymnasium==0.28.1
ipykernel==6.19.2
matplotlib==3.7.1
numpy==1.23.5
pandas==2.0.3
seaborn==0.12.2
scikit-learn==1.3.0
tensorflow==2.10.0
tensorflow-datasets==1.2.0
transformers==4.29.2
pandas==2.3.3
ipykernel==7.3.0
matplotlib==3.10.9
scikit-learn==1.7.2
```
All the requirements above can be installed using Python package installer (pip):  
`pip install -r requirements.txt`

> **Extra notes**: tensorflow GPU acceleration only works on CUDA version 11.2, which is older version. This current setup doesn't work with newer generation GPU

### 3. Git Clone
If you want to download all the codes into your own local devices, you can use git with this command:   
`git clone https://github.com/britoddd/lab-semester-5.git`

## Contributor
**@britoddd** (Brian Nicholas )