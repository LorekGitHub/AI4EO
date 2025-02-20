# Week 4: Unsupervised Learning Methods in AI4EO

This folder contains materials for **Week 4** of the AI4EO project, focusing on **Unsupervised Learning Methods** for Earth Observation (EO) data.

## 📌 Overview
In this week’s module, we explore **unsupervised learning techniques** applied to **Sentinel-2 optical data** and **Sentinel-3 altimetry data**. These methods help analyze and classify different environmental features **without labeled training data**. We then plot the echo waveforms for ice and leads, aligning the waveforms using cross-correlation. We use a confusion matrix to compare our GMM classification with true labels from the ESA dataset.

The tasks in this notebook include:
1. **Discriminating Sea Ice and Leads** using **Sentinel-2 optical data**.
2. **Discriminating Sea Ice and Leads** using **Sentinel-3 altimetry data**.

## 📂 Contents
- 📓 **`Chapter1_Unsupervised_Learning_Methods.ipynb`**  
  This Jupyter Notebook provides a practical introduction to **K-Means Clustering** and other **Gaussian Mixture Models (GMM)** applied to EO data.

- 📝 **README.md**  
  This file explains the contents of the Week 4 folder.

## 📊 Methods & Techniques
- **K-Means Clustering**: Used to group similar pixel values in EO images.
- **Gaussian Mixture Models**: GMM provides the probability of each data point belonging to each cluster, offering a soft classification and understanding of the uncertainties in our data. They allow clusters to have different sizes and shapes, allowing for more flexible classification.
- **Feature Extraction**: Identifying key patterns in the data.
- **Data Preprocessing**: Handling Sentinel-2 and Sentinel-3 data for analysis.

## 🔧 Dependencies
To run the notebook, ensure you have the following Python libraries installed:
```sh
pip install rasterio netCDF4 numpy pandas scikit-learn matplotlib seaborn
;;'
### Run Locally:
1. Clone the repository:
   ```sh
   git clone https://github.com/LorekGitHub/AI4EO.git

