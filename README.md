# Modeling & Analysis Code

This repository contains all code, cleaned data, and results for our comparative modeling study using CatBoost, HistGradientBoosting, LightGBM, TabTransformer, and TabNet, along with data‑cleaning and sample‑extraction scripts.

---

## 📂 Files & Notebooks

| Filename                                  | Description                                                      |
|-------------------------------------------|------------------------------------------------------------------|
| **CatBoost Modelling.ipynb**              | CatBoost modelling code                                          |
| **HistGradientBoosting_Modelling.ipynb**  | Hist Gradient Classifier modelling code                          |
| **LightGBM_Modelling.ipynb**              | LightGBM modelling code                                          |
| **Tab_Transformer_Modelling.ipynb**       | Tab Transformer modelling code                                   |
| **TabNet_Modelling.ipynb**                | TabNet modelling code                                            |
| **Final Data Cleaning (Test).Rmd**        | Final data cleaning for **test** set (incl. sine/cosine transforms) |
| **Final Data Cleaning (Train).Rmd**       | Final data cleaning for **train** set (incl. sine/cosine transforms)|
| **Sample Extraction of Train.Rmd**        | Sample extraction script for training set                        |

---

## 🔗 Google Drive Folder

You can find all raw notebooks, datasets, analyses, and results here:  
[Google Drive Folder](https://drive.google.com/drive/folders/1__yIOXnz5ExNXI1e-uAAzDJL2rJfb4oC?usp=sharing)

---

## 📁 Folder Structure on Drive

- **Codes**  
  Contains all model notebooks in Google Colab format.
- **Datasets**  
  Fully cleaned **Train** and **Test** datasets (after all transformations).
- **Excel Sheet Based Analysis**  
  Visual summaries: plots, averages, and top‑5 result tables.
- **Results**  
  Model outputs: confusion matrices, performance metrics, and 15 sample test predictions.

---

##  To Run the Codes (in Google Colab)

1. **Mount Google Drive**
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
2. **Load the Test and Train dataset paths**
   ```python
   train_dir = "/content/drive/MyDrive/Big Data Analysis and Project - a1906525/Datasets/crime_train_final.csv"
   test_dir = "/content/drive/MyDrive/Big Data Analysis and Project - a1906525/Datasets/crime_test_cleaned.csv"
3. **Modelling**
   As the modelling parts of LightGBM, CatBoost, HGB Classifier were run on L4 GPU, change the runtime type if needed. 

