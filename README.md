# Deep Learning Challenge 21

## Introduction

This project is focused on building and evaluating neural network models using the charity data provided. The dataset is processed and analyzed to create models that predict outcomes based on the given features. The entire workflow, from data preparation to model evaluation, was executed on Google Colab, leveraging its cloud-based environment to manage and process the data efficiently.

## Process and Methodology

1. **Data Preparation:**
   - The dataset was imported directly from a URL into a pandas DataFrame.
   - Data cleaning and preprocessing steps were performed, including handling missing values and feature scaling.
   - The dataset was split into training and testing sets.

2. **Model Building:**
   - Several neural network models were designed and trained using TensorFlow and Keras.
   - Models with varying architectures were evaluated to find the optimal configuration.

3. **Model Evaluation:**
   - Each model's performance was assessed based on accuracy and loss metrics.
   - The models were saved in `.h5` format for future use and comparison.

4. **Results Documentation:**
   - Evaluation results and visualizations were documented in a Word report.
   - Screenshots of code execution and results were captured for reference.

## Files Contained in the Repository

- **Main Folder: `Deep_learning_Challange21`**
  - **`Deep Learning_Challange` Folder:**
    - **`Resources` Folder:**
      - `charity_data.csv`: The dataset used for model training and evaluation.
    - **`h5_files` Folder:**
      - Contains the following `.h5` files:
        - `AlphabetSoupCharity_Optimization_1.h5`
        - `AlphabetSoupCharity_Optimization_2.h5`
        - `AlphabetSoupCharity_Optimization_3.h5`
        - `Starter_code_final.h5`
    - **`Images` Folder:**
      - Contains screenshots of code execution and evaluation results.
    - **`AlphabetSoupCharity_optimization_1.ipynb`**: Jupyter Notebook with neural network model 1.
    - **`AlphabetSoupCharity_optimization_2.ipynb`**: Jupyter Notebook with neural network model 2.
    - **`AlphabetSoupCharity_optimization_3.ipynb`**: Jupyter Notebook with neural network model 3.
    - **`Starter_code_final.ipynb`**: Jupyter Notebook with the final starter code.
    - **`Analysis and Report.docx`**: A detailed report summarizing the analysis, results, and methodologies.

## Notes

- All code execution and model training were performed using Google Colab, which provided a cloud-based environment for running the models and managing the files.
- The `.h5` files contain the saved models and can be used for further evaluation or deployment.

Feel free to explore the files and check the provided documentation for a detailed understanding of the project's execution and outcomes.

