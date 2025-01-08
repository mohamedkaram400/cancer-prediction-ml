# **Cancer Prediction Project**

This project is a machine learning-based cancer prediction tool using the Logistic Regression algorithm. Follow the steps below to set up and run the project after cloning it.

---

## **Prerequisites**
1. Install [Anaconda](https://www.anaconda.com/) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html).
2. Clone the repository using Git:
   ```bash
   git clone https://github.com/mohamedkaram400/cancer-prediction-ml.git
   cd cancer-prediction-ml

## Option 1: Create environment using environment.yml
conda create --name cancer_prediction --file environment.yml

## OR Option 2: Manually create and install dependencies
conda create --name cancer_prediction python=3.8
conda activate cancer_prediction
conda install numpy=1.21.2 pandas=1.3.3 scikit-learn=0.24.2 matplotlib=3.4.3 jupyter
pip install tensorflow==2.6.0 keras==2.6.0

## Activate the environment
conda activate cancer_prediction

## Launch the Jupyter Notebook
jupyter notebook
