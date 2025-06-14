# Machine Learning Model

This project contains the source code and relevant dataset for a machine learning model that aims to predict the quality of bananas. 

It mainly employs two machine learning models - Logistic Regression and Random Forest Classification - to predict the attribute "quality_category," and Random Forest Regression to predict the attribute "quality_score," all using the dataset's other attributes.

The file "banana_quality_prediction_model.ipynb" is a Jupyter Notebook containing the code used in the training and testing of the machine learning models. More detail can be found in the notebook itself under the "Instructions" section.

# Dataset Overview

The dataset "banana_quality_dataset.csv" contains 1000 banana samples with 16 different attributes that each refer to a different characteristic the banana possesses. This dataset was retrieved from kaggle, titled [Banana Quality Dataset](https://www.kaggle.com/datasets/mrmars1010/banana-quality-dataset). The following block code contains the explanation for each attribute found within the dataset:
```
- sample_id: A unique identifier assigned to each banana sample in the dataset. This allows the samples to be tracked and referenced uniquely.

- variety: The cultivar or breed of banana, such as Cavendish, Red Dacca, or Lady Finger. Knowing the specific banana variety provides context about the sample's physical characteristics and growing conditions.

- region: The geographic origin of the banana, such as Ecuador, Philippines, or Costa Rica. The region can influence factors like climate, soil, and growing practices that impact the banana's qualities.

- quality_score: A numerical score, likely on a scale of 1-4 that rates the overall quality of the banana sample. This could encompass factors like appearance, texture, and lack of defects.

- quality_category: A text label that categorizes the quality score into broader groupings like "Excellent" etc
This provides an easier-to-understand quality assessment.

- ripeness_index: A numerical index representing the ripeness level of the banana, potentially ranging from 1 (green/unripe) to 10 (overripe). This quantifies the maturity of the fruit.

- ripeness_category: A text label like "Green", "Yellow", "Ripe", or "Overripe" that corresponds to the ripeness index. This gives a clear, qualitative ripeness classification.

- sugar_content_brix: The sugar content of the banana measured in degrees Brix. This is a common way to assess the sweetness and quality of the fruit.

- firmness_kgf: The firmness of the banana measured in kilograms-force. This indicates the texture and maturity of the sample.

- length_cm: The physical length of the banana in centimeters. This size metric can vary by variety and growing conditions.

- weight_g: The physical weight of each banana in grams.

- harvest_date: The date wherein the banana sample was harvested from its tree. All values within this attribute are of the data type "datetime"

- tree_age_years: The age of the tree the banana was harvested from in years.

- altitude_m: The banana tree's recorded altitude above sea level in meters.

- rainfall_mm: The total rainfall received during the banana growing period, measured in millimeters

- soil_nitrogen_ppm: The concentration of nitrogen in the soil, measured in parts per million.