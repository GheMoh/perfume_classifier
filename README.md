# Perfume Classifier

## Introduction
The "Perfume Classifier" project aims to develop a machine learning model capable of classifying perfumes based on measurements obtained from an olfactometer. An olfactometer is an instrument used to assess the sensitivity of the sense of smell, particularly concerning the intensity, concentration, or quality of odors. It does this by diluting a fragrance sample with odor-neutral air and presenting it to a panel for evaluation.

## Project Workflow

1. **Importing Libraries:** The project begins by importing essential Python libraries for data manipulation and machine learning, including NumPy, pandas, Matplotlib, Seaborn, and scikit-learn. These libraries are crucial for various tasks in the project.

2. **Reading the Dataset:** The dataset is read from an Excel file named 'dataset.xlsx' using pandas, and its initial contents are displayed.

3. **Data Preprocessing:** Some initial data preprocessing is performed, including renaming columns and reorganizing the dataset to create a more structured dataframe for analysis.

4. **Obtaining Perfume Names:** The list of perfume names is extracted from the dataset.

5. **Checking for Missing Values:** The dataset is checked for missing values to ensure data quality.

6. **Creating a New Dataframe:** A new dataframe is created with two columns, one for the olfactometer readings and the other for the corresponding perfume labels.

7. **Labeling Observations:** The olfactometer readings are labeled with the corresponding perfume scent to create a structured dataset.

8. **Dataframe Information:** Information about the size and structure of the new dataframe is provided.

9. **Shuffling the Dataset:** The dataset is shuffled to prevent any potential bias in the model training process.

10. **Statistical Analysis:** Descriptive statistics and visual representations of the data are generated to better understand the dataset.

11. **Encoding Labels:** The perfume labels are encoded into numerical values to prepare them for machine learning algorithms.

12. **Data Splitting:** The dataset is split into training and testing sets to train and evaluate machine learning models.

13. **Building and Evaluating Models:**
    - **Decision Tree Classifier:** A decision tree classifier is created and evaluated for accuracy on the testing dataset.
    - **Random Forest Classifier:** A random forest classifier with 200 estimators is built and evaluated for accuracy on the testing dataset.

14. **Conclusion:** Both models yield high accuracy scores, but the decision tree classifier is identified as the superior choice for classifying perfumes based on the olfactometer measurements.

The "Perfume Classifier" project demonstrates the process of data preprocessing, exploratory data analysis, model training, and evaluation in the context of perfume classification using machine learning techniques. The decision tree classifier is recommended for practical use in classifying perfumes based on olfactometer measurements.
