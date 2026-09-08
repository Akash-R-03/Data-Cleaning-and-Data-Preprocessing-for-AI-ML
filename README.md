# Data Cleaning and Data Preprocessing for AI/ML

This repository contains practical Python and Jupyter Notebook implementations for **Data Cleaning and Data Preprocessing**, which are important steps in preparing raw data for machine learning models.

The sprint focuses on identifying data quality issues, cleaning datasets, transforming features, handling missing values and outliers, encoding categorical variables, scaling numerical features, preventing data leakage, and building preprocessing workflows.

## Objective

The main objective of this sprint is to understand how raw datasets can be transformed into clean, validated, and machine-learning-ready data.

### Workflow

Raw Data → Data Inspection → Data Cleaning → Data Validation → Data Transformation → Feature Preparation → Data Splitting → Preprocessing Pipeline → ML-Ready Data

## Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn

## Dataset

The notebooks primarily use the **Titanic Dataset** for practical demonstrations.

Dataset file:

`Titanic-Dataset.csv`

The dataset contains passenger information such as age, gender, passenger class, fare, family relationships, and survival status.

## Notebooks

| No. | Notebook | Topics Covered |
|---|---|---|
| 01 | `01_Data_Preprocessing_Basics.ipynb` | Data preprocessing fundamentals and preprocessing workflow |
| 02 | `02_Data_Type_Handling.ipynb` | Data types and type conversions |
| 03 | `03_Missing_Value_Handling.ipynb` | Missing value detection and treatment |
| 04 | `04_Duplicate_Data.ipynb` | Duplicate detection and removal |
| 05 | `05_Data_Validation.ipynb` | Data quality and validation rules |
| 06 | `06_Outlier_Treatment.ipynb` | Outlier detection and treatment |
| 07 | `07_Categorical_Encoding.ipynb` | Encoding categorical variables |
| 08 | `08_Feature_Scaling.ipynb` | Normalization and standardization |
| 09 | `09_Data_Transformation.ipynb` | Mathematical and distribution transformations |
| 10 | `10_Feature_Selection.ipynb` | Feature relevance and selection techniques |
| 11 | `11_Imbalanced_Data.ipynb` | Class imbalance and sampling techniques |
| 12 | `12_Data_Splitting.ipynb` | Train, validation, and test splitting |
| 13 | `13_Data_Leakage.ipynb` | Identifying and preventing data leakage |
| 14 | `14_Preprocessing_Pipeline.ipynb` | Scikit-learn preprocessing pipelines |
| 15 | `15_Before_After_Preprocessing.ipynb` | Before and after preprocessing comparison |
| 16 | `16_Complete_Preprocessing_Workflow.ipynb` | Complete end-to-end preprocessing workflow |
| 17 | `17_Mini_Assessment.ipynb` | Preprocessing concepts and coding assessment |

## Key Concepts

### Data Cleaning
- Missing value handling
- Duplicate removal
- Invalid value detection
- Data type correction
- Data validation
- Outlier treatment

### Data Preprocessing
- Categorical encoding
- Feature scaling
- Data transformation
- Feature selection
- Handling imbalanced data
- Train/validation/test splitting

### Machine Learning Best Practices
- Preventing data leakage
- Fitting preprocessing steps only on training data
- Using `Pipeline`
- Using `ColumnTransformer`
- Maintaining consistent preprocessing between training and testing data
- Validating the final ML-ready dataset

## Preprocessing Documentation

Important preprocessing decisions are documented using:

- Problem
- Analysis
- Technique Selected
- Reason
- Implementation
- Result
- Impact

This helps explain not only **what was changed**, but also **why the change was necessary** and how it affects machine learning.

## Learning Outcome

After completing this sprint, the learner should be able to:

- Understand common data quality problems
- Clean and validate raw datasets
- Handle missing values appropriately
- Detect and treat outliers
- Encode categorical variables
- Scale and transform numerical features
- Select relevant features
- Handle imbalanced datasets
- Split data correctly
- Identify and prevent data leakage
- Build reusable preprocessing pipelines
- Prepare datasets for machine learning

## Repository Structure

```text
Data-Cleaning-and-Data-Preprocessing-for-AI-ML/
│
├── 01_Data_Preprocessing_Basics.ipynb
├── 02_Data_Type_Handling.ipynb
├── 03_Missing_Value_Handling.ipynb
├── 04_Duplicate_Data.ipynb
├── 05_Data_Validation.ipynb
├── 06_Outlier_Treatment.ipynb
├── 07_Categorical_Encoding.ipynb
├── 08_Feature_Scaling.ipynb
├── 09_Data_Transformation.ipynb
├── 10_Feature_Selection.ipynb
├── 11_Imbalanced_Data.ipynb
├── 12_Data_Splitting.ipynb
├── 13_Data_Leakage.ipynb
├── 14_Preprocessing_Pipeline.ipynb
├── 15_Before_After_Preprocessing.ipynb
├── 16_Complete_Preprocessing_Workflow.ipynb
├── 17_Mini_Assessment.ipynb
└── README.md
