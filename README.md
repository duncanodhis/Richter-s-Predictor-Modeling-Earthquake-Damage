# Richter's Predictor: Modeling Earthquake Damage

Richter's Predictor is a machine learning project aimed at predicting the ordinal variable `damage_grade`, which represents the level of damage to buildings hit by earthquakes. The model categorizes damage into three grades:

- **Grade 1**: Low damage
- **Grade 2**: Medium damage
- **Grade 3**: Almost complete destruction

The project utilizes a dataset containing various features related to building characteristics and seismic properties to train predictive models.

## Data

The dataset used in this project contains features such as building age, height, location, construction materials, and seismic intensity, among others. Each instance in the dataset is labeled with the corresponding `damage_grade`, indicating the level of damage observed in the building after an earthquake event.

### Features
- **Building Age**: The age of the building in years.
- **Height**: The height of the building in stories.
- **Location**: Geographic coordinates or region where the building is situated.
- **Construction Type**: The type of construction materials used in the building.
- **Seismic Intensity**: Measures of the earthquake's magnitude and intensity.

### Target Variable
- **Damage Grade**: The level of damage observed in the building after an earthquake, categorized into three grades: low damage, medium damage, and almost complete destruction.

## Approach

The predictive model is developed using machine learning techniques, particularly focusing on classification algorithms suitable for ordinal variables. The project follows these main steps:

1. **Data Preprocessing**: Handle missing values, encode categorical variables, and perform feature scaling if necessary.
  
2. **Exploratory Data Analysis (EDA)**: Explore the relationships between features and the target variable to gain insights into the data.

3. **Model Development**: Train and evaluate various classification algorithms such as Random Forest, Gradient Boosting, and Neural Networks to predict the `damage_grade`.

4. **Model Evaluation**: Assess the performance of the trained models using appropriate evaluation metrics such as F1-score, accuracy, and confusion matrix.

## Results

After thorough experimentation and evaluation, the model achieves an F1-micro score of 0.7. This indicates that the model performs well in classifying the damage grades across all classes, considering both precision and recall.

## Repository Structure

- `data/`: Contains the dataset used for training and evaluation.
- `notebooks/`: Jupyter notebooks detailing the data exploration, preprocessing, model development, and evaluation.
- `models/`: Saved trained models.
- `README.md`: This file providing an overview of the project.

## Requirements

- Python 3.x
- Required libraries (NumPy, pandas, scikit-learn, etc.)
