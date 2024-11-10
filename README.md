# Rainfall Forecasting with AI 

This repository contains the code on leveraging AI to forecast rainfall. The project involves data preprocessing, model training, and visualization to predict rainfall and compare it with real-world data from AWS (Automated Weather Station) stations in Vietnam.

## Repository Structure 
 
- **`preprocess.ipynb`** 
This notebook is responsible for:
  - Extracting information and creating tabular data from GEOTIFF files.

  - Handling missing values and outliers in the extracted data.
 
- **`models.ipynb`** 
This notebook implements various machine learning models for rainfall forecasting. Additionally, it uses an ensemble meta-model to combine the outputs of individual models, aiming to improve prediction accuracy.
 
- **`Result and Map.ipynb`** 
This notebook:
  - Generates predicted rainfall maps.

  - Compares the predicted maps with ground truth maps from AWS station data, providing a visual assessment of model performance.
 
- **`Coordinate.ipynb`** 
This notebook extracts coordinates of various provinces in Vietnam, which are used to draw provincial boundaries on the maps generated in `Result and Map.ipynb`.
