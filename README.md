# Capstone Propasal Handwritten Devnagri Character & Numeral Recognition using Deep Learning
### Nisha Gadhe
### May 2018

This is the capstone project going on in Udacity. This project used dataset which has been extracted from kaggle. This project has goal is to predict the handwritten Devanagari Consonant characters & Numeral characters in an image. The dataset contains images of handwritten devnagri Consonants & Numeral characters which can be used to train and test the model.

# Software and Libraries
This project requires the following Python libraries installed:

- Anaconda2 / Python 2.7.x or Python 3.X.X
- Numpy
- Matplotlib
- Tensorflow
- Keras
- OpenCV
- Jupyter Notebook
- (Optional) A GPU with Cuda support is highly recommended for fast computation.
- Install respective graphics drivers, cuda toolkit, cudnn, tensorflow-gpu version
Jupyter Notebook is needed to run and execute project.

If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, which already has the above packages and more included.

# Dataset
The datasets are hosted in a Kaggle competition. Please download data from the link provided. This dataset contain Devanagari Characters. It comprises of 92000 images [32x32 px] corresponding to 46 characters, consonants "ka" to "gya", and the digits 0 to 9. The vowels are missing. The CSV file is of the dimension 92000 * 1025. There are 1024 input features of pixel values in grayscale (0 to 255). The column "character" represents the Devanagari Character Name corresponding to each image. There are 46 classes present out of which 10 classes for digits & 36 classes for characters & each class has 2000 images.

https://www.kaggle.com/rishianand/devanagari-character-set

# Input
These Devanagari Consonants characters & Numeral characters were originally written on a A4 size white paper after which were scanned and then cropped manually.

# Project Submission Files
- Capstone Project Report: project_report.pdf
- Capstone Proposal: proposal.pdf
- devimg_refine/ folder contain input images
- input/ folder contain downloaded dataset
- DCNDR_with_refined_DNN.ipynb Contain actual source code
- DCNDR_with_refined_DNN.html Contain actual source code in html format
- README.html

