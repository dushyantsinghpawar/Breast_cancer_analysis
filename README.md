# Breast Cancer Classification Project

## Introduction
This project is part of the machine learning course at University of North Carolina at Charlotte, aiming to analyze and classify breast cancer tumors as malignant or benign using various machine learning models. The dataset for this project was generously provided by Dr. Hongfei Xue, who is also the instructor for the course.

## Dataset
The Training dataset consists of 398 training samples and 167 testing samples, each with 30 features, 1 ID number, and a binary prediction class. The target variable is labeled as "M" for malignant and "B" for benign. To note, the dataset includes missing values, which are addressed through regression-based imputation techniques.

## Project Objectives
1. **Data Pre-processing:**
   - Read the dataset from original CSV files.
   - Perform missing data imputation using regression algorithms.
   - Normalize the dataset.

2. **Data Visualization:**
   - Conduct Principal Component Analysis (PCA) to reduce feature dimensions to 2.
   - Visualize the dataset in 2D, labeling data points with red for malignant and blue for benign.

3. **Machine Learning Models Implementation:**
   - Logistic Regression with Regularizer.
   - Support Vector Machine (SVM).
   - Neural Network.
   - Decision Tree.
   - K-Nearest Neighbors (KNN).
   - Fine-tune hyperparameters and evaluate models on the testing dataset.

4. **Comparison and Analysis:**
   - Compare the performances of all five algorithms using metrics: accuracy, precision, recall, and F1 score.
   - Discuss the advantages and disadvantages of each algorithm.

## Usage
- Execute the code in a sequential manner, following the instructions in each section.
- Ensure Python 3 is installed.
- Install required Python packages using:
  ```
  pip install -r requirements.txt
  ```

## File Descriptions
- `train.csv`: Training dataset.
- `test.csv`: Testing dataset.
- `BreastCancerClassification.ipynb`: Jupyter Notebook containing the entire analysis.

## Results
The project results, including model performances and visualizations, can be found in the notebook.

## Acknowledgments
- This project is part of the [Course Name] at [Your University Name].
- The dataset was graciously provided by [Professor Name], who also serves as the instructor for the course.

Feel free to contribute, report issues, or provide feedback. Happy coding!
