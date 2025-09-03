# Spam Classifier (Hands-On ML Exercise)

This project is an implementation of the spam classification exercise from the book  
*Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow* by Aurélien Géron.  

The notebook trains a spam vs ham classifier using the [SpamAssassin dataset](http://spamassassin.apache.org/).

---

## Contents
- `datasets/` → SpamAssassin dataset used for training
- `spam_classifier.ipynb` → Jupyter notebook with preprocessing, model training, and evaluation
- `environment.yml` → Conda environment with required dependencies

---

## Setup
```bash
conda env create -f environment.yml
conda activate spam_classifier
jupyter notebook
