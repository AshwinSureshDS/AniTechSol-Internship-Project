# Stroke Analysis and Prediction

## Overview
This project focuses on analyzing stroke data and building predictive models to identify risk factors associated with stroke occurrences. The analysis is performed using a Jupyter notebook that explores various aspects of the healthcare dataset related to strokes.

## Dataset
The project uses the 'healthcare-dataset-stroke-data.csv' dataset, which contains the following features:
- id: Unique identifier
- gender: Gender of the patient (Male/Female)
- age: Age of the patient
- hypertension: Whether the patient has hypertension (0/1)
- heart_disease: Whether the patient has heart disease (0/1)
- ever_married: Whether the patient has ever been married (Yes/No)
- work_type: Type of work (Private, Self-employed, Govt_job, etc.)
- Residence_type: Type of residence (Urban/Rural)
- avg_glucose_level: Average glucose level in blood
- bmi: Body Mass Index
- smoking_status: Smoking status of the patient
- stroke: Whether the patient had a stroke (1) or not (0) - Target variable

## Analysis Performed

### 1. Data Exploration and Cleaning
- Statistical analysis of numerical features
- Distribution analysis of categorical variables
- Handling missing values
- Data type conversion

### 2. Descriptive Analysis
- Comprehensive statistical measures for numerical columns
- Distribution of categorical variables
- Identification of prevalent categories associated with stroke occurrences

### 3. Demographic Analysis
- Age and gender distribution
- Analysis of health conditions across different demographic groups

### 4. Risk Factor Analysis
- Identification of significant risk factors for stroke
- Analysis of lifestyle factors (smoking, BMI) impact on stroke occurrences
- Determination of risk factor combinations

### 5. Feature Engineering
- Creation of age groups and BMI categories
- Extraction of additional features from existing columns

### 6. Data Visualization
- Distribution of stroke occurrences using various charts
- Visualization of relationships between features and stroke occurrences

### 7. Predictive Modeling
- Building classification models (Logistic Regression, Decision Trees, Random Forest)
- Model evaluation using appropriate metrics
- Comparison of different algorithms' performance

## Installation

1. Clone this repository
2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```
3. Ensure you have the dataset file 'healthcare-dataset-stroke-data.csv' in the project directory

## Usage

1. Open the Jupyter notebook 'Stroke Analysis and Prediction.ipynb'
2. Run the cells sequentially to perform the analysis
3. Modify parameters or try different models as needed

## Requirements

See requirements.txt for a list of required Python packages.

## Python Version

This project was developed using Python 3.11.7.