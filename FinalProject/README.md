# GEOL0069 - UCL - Project - Cloud/Snow/Ice Classification and Explainable AI Examples

This repository contains:

A description of the ML problem to be tackled,
A figure illustrating the remote sensing technique and AI algorithm's implementation,
Sound documentation in the accompanying Jupyter Notebook,
A video recording link that explains the code,
An assessment of the environmental cost of this project.

Monitoring and distinguishing between snow, ice, and cloud in high-resolution satellite imagery is a critical task for a wide range of environmental and climate-related applications. This distinction is particularly important in alpine and mountainous regions, where persistent cloud cover, complex topography, and limited in-situ observations make traditional monitoring difficult.

Accurate classification of snow and clouds can support:

🌊 Hydrological modeling (e.g., snowmelt prediction),

🏔️ Alpinism, Glacier and ice monitoring,

⚠️ Disaster risk assessments (e.g., avalanches, landslides),

🌡️ Climate change studies.

However, these surface types often share similar spectral signatures in optical satellite imagery, making them difficult to separate without advanced methods.

This project uses Sentinel-2 Level-2A imagery (10m–20m resolution) and explores the ability to classify snow vs. cloud pixels using a combination of:

Spectral features from multiple Sentinel-2 bands,

Scene Classification Layer (SCL) labels for training,

Explainable AI (XAI) techniques, particularly SHAP (SHapley Additive exPlanations), to identify which spectral bands contribute most to the model’s decisions.

By training a classifier (e.g., XGBoost) on labeled data and evaluating performance across spatially separated regions, we aim to improve model transparency and performance in complex terrains. The integration of XAI provides insight into spectral importance and helps inform model optimisation, primarily through more efficient training regarding the classification of snow/ice/cloud variables.
