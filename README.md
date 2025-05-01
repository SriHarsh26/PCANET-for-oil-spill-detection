# PCANet-Based Hyperspectral Image Classification for Oil Spill Detection

This repository contains the implementation of a project titled **PCANet-Based Hyperspectral Image Classification for Oil Spill Detection**, developed as part of the B.E. final year project at Vasavi College of Engineering.

## 🌊 Project Overview

Hyperspectral Imaging (HSI) enables detailed detection of materials based on spectral signatures. This project leverages **PCANet**, a lightweight and unsupervised deep learning model, to classify oil spills from HSI data. It combines Principal Component Analysis (PCA) for feature extraction with a Support Vector Machine (SVM) classifier for accurate, efficient oil spill detection.

## 📁 Dataset

We use the **Hyperspectral Oil Spill Detection (HOSD)** dataset developed from AVIRIS sensor data.

**Download Link:**  
📥 [HOSD Dataset](https://www.kaggle.com/datasets/avenkatsriharsha/hsi-complete)

> **Note:** Place the `.mat` file in the same working directory where the notebook is running, or update the path in the code accordingly.

---

## 🧪 Notebook: `pcanet (1).ipynb`

### Usage on Kaggle

To run this notebook in a **Kaggle Notebook Environment**:

1. **Upload Files:**
   - Upload the notebook `pcanet (1).ipynb` and the dataset file `GM01.mat` to your Kaggle session.
   - Ensure GPU is enabled (`Settings > Accelerator > GPU` - preferably NVIDIA T4).

2. **Install Required Packages:**
   If not pre-installed in Kaggle, install missing packages using:
   ```python
   !pip install spectral chainer tqdm

3. **Run the Notebook:**

   - The notebook is organized into training and testing sections.
   
   - It uses PCANet for feature extraction and an SVM for classification.
   
   - The final output includes:
   
      - Test accuracy
   
      - Confusion matrix
   
      - Side-by-side visualization of Ground Truth vs Predicted Output

4. Customize Dataset Path: If needed, modify the dataset path:

    ```python
    path = "/kaggle/input/gm01/GM01.mat"
   
**Requirements**
   - Python 3.8+
   - NumPy
   - SciPy
   - Scikit-learn
   - Chainer
   - Spectral
   - Matplotlib
   - TQDM


**License**

   This project is for academic and research use only.

