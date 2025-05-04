# Unsupervised Learning

## K-Means Clustering
- **Description**: Partitions data into K clusters by minimizing within-cluster variance.
- **Dataset**: [Customer Segmentation](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
  - 200 samples, 5 features (CustomerID, Gender, Age, Annual Income, Spending Score).
  - Used features: Annual Income (k$), Spending Score (1-100).
  - Preprocessing: Scaled features using StandardScaler.
- **Reproducibility**:
  - Install Kaggle API: `!pip install kaggle`.
  - Upload `kaggle.json` and set permissions: `!mkdir -p ~/.kaggle; !cp kaggle.json ~/.kaggle/; !chmod 600 ~/.kaggle/kaggle.json`.
  - Download dataset: `!kaggle datasets download -d vjchoudhary7/customer-segmentation-tutorial-in-python`.
  - Unzip and run `KMeans.ipynb`.

## DBSCAN
- **Description**: Clusters data based on density, identifying noise points.
- **Dataset**: [Wine Quality](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009)
  - 1599 samples, 12 features (e.g., alcohol, pH).
  - Used features: alcohol, pH, volatile acidity, fixed acidity.
  - Preprocessing: Scaled features.
- **Reproducibility**:
  - Install Kaggle API and set up `kaggle.json`.
  - Download dataset: `!kaggle datasets download -d uciml/red-wine-quality-cortez-et-al-2009`.
  - Unzip and run `DBSCAN.ipynb`.

## Principal Component Analysis (PCA)
- **Description**: Reduces dimensionality by projecting data onto principal components.
- **Dataset**: [Heart Disease UCI](https://www.kaggle.com/datasets/ronitf/heart-disease-uci)
  - 303 samples, 14 features (e.g., age, cholesterol).
  - Used features: All numerical features except target.
  - Preprocessing: Scaled features.
- **Reproducibility**:
  - Install Kaggle API and set up `kaggle.json`.
  - Download dataset: `!kaggle datasets download -d ronitf/heart-disease-uci`.
  - Unzip and run `PCA.ipynb`.

## Image Compression with Singular Value Decomposition (SVD)
- **Description**: Compresses images by retaining top singular values.
- **Dataset**: [Digit Recognizer](https://www.kaggle.com/competitions/digit-recognizer)
  - 42000 samples, 784 pixel features (28x28 images).
  - Preprocessing: Reshaped pixel values into 28x28 matrices, normalized.
- **Reproducibility**:
  - Install Kaggle API and set up `kaggle.json`.
  - Download dataset: `!kaggle competitions download -c digit-recognizer`.
  - Unzip and run `SVD.ipynb`.