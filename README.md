# Prostate-Cancer-Prediction-With-OmniXAI

## Introduction
The prostate gland is a small component of the male reproductive system, roughly the size and shape of a walnut. It is situated in the pelvis, below the bladder, and in front of the rectum. Prostate cancer is a condition where cancer cells develop within the tissues of the prostate. Unlike many other forms of cancer, prostate cancer tends to progress slowly, often taking several years for symptoms to manifest. To diagnose prostate cancer, medical professionals frequently perform a digital rectal exam (DRE). This procedure involves a brief examination of the prostate's size, texture, rigidity, and the detection of any abnormalities such as hard spots, lumps, or growths that extend beyond the prostate. Any discomfort experienced during the examination is also noted (National Cancer Institute, 2023).

## Prostate Dataset
The Prostate Dataset contains records for 100 patients, including ten variables (eight numeric and one categorical variable, ID). The dataset, as described by Celik in 2020, includes the following variables:

- ID: A unique patient record number.
- diagnosis_result: A categorical variable indicating the diagnosis result, either 'B' for Benign or 'M' for Malignant.
- radius: Denotes the prostate cell radius.
- texture: Prostate cell texture.
- perimeter: The circumference of the prostate cell.
- area: Prostate cell area.
- smoothness: Prostate cell smoothness.
- compactness: The volume of the prostate cell.
- symmetry: A measure of the quality of symmetry.
- fractal_dimension: A combined measure representing both compactness and symmetry.


## Code Implementation

Google Colab was used to implement this project. At the initial stage, the necessary packages were installed on Google Colab. The packages installed are omnixai, dash and interpret. Dash is a Python framework used to build data visualization dashboards. Omnixai and interpret are the packages containing the libraries needed for the usage of the OmniXAI framework. Once the packages had been installed, the needed libraries for the tabular data predictions were installed. These libraries also included LIME and SHAP explainers from the selected integrated frameworks. The prostate cancer tabular dataset was uploaded to Google Colab and imported using the file directory on Google Colab.


## Usage
You can utilize this dataset for various purposes, such as:

- Prostate Cancer Research: Analyze the dataset to identify patterns or factors that may be associated with prostate cancer diagnosis.
- Machine Learning: Develop predictive models to classify new cases as Benign or Malignant based on the provided features.
- Statistical Analysis: Perform statistical tests and exploratory data analysis to gain insights into the dataset.




## References
- Cancer Research UK (2023) Examination of your prostate, https://www.cancerresearchuk.org/about-cancer/tests-and-scans/examination-prostate.
- Celik, S. (2020) Prostate Cancer Analysis with ML Methods, https://www.kaggle.com/code/sadielik/prostate-cancer-analysis-with-ml-methods.
- Mcleod, S. (2023) Correlation in Statistics: Meaning, Types, Examples & coefficient, https://www.simplypsychology.org/correlation.html.
- National Cancer Institute (2023) Understanding Prostate Changes: A Health Guide for Men , https://www.cancer.gov/types/prostate/understanding-prostate-changes.
