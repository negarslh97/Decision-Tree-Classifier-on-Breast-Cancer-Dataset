
# Decision Tree Classifier on Breast Cancer Dataset

## Overview
This project demonstrates the implementation of a **Decision Tree Classifier** to classify breast cancer data. The goal is to train, test, and evaluate the model using the well-known breast cancer dataset.

## Dataset
The dataset used in this project is the **Breast Cancer Dataset** from the `sklearn.datasets` library. This dataset contains 30 features related to characteristics of cell nuclei present in breast cancer biopsies.

## Project Structure
The Jupyter Notebook consists of the following sections:

1. **Data Loading**: 
   - Load the breast cancer dataset using the `load_breast_cancer` function from the `sklearn.datasets` library.
   
2. **Data Preprocessing**: 
   - Split the dataset into training and testing sets using the `train_test_split` method.

3. **Model Training**:
   - Train a **Decision Tree Classifier** using the training data.

4. **Model Evaluation**:
   - Test the classifier on the testing set and evaluate its performance.
   - Answer specific questions related to the model's behavior.

## Libraries Used
- **Pandas**: For handling data manipulation.
- **NumPy**: For numerical operations.
- **Matplotlib**: For data visualization.
- **scikit-learn**: For machine learning models, including decision tree, data splitting, and metrics evaluation.

## Instructions to Run the Project
1. Make sure you have Jupyter Notebook installed on your machine.
2. Install the necessary libraries by running:
   ```
   pip install numpy pandas scikit-learn matplotlib
   ```
3. Open the `classification.ipynb` notebook in Jupyter.
4. Follow the instructions in each cell to execute the code and answer the questions provided.

## Questions to be Answered
The notebook includes tasks that require answering several key questions:
1. How does the decision tree behave on this dataset?
2. What is the accuracy of the model?
3. How does feature importance affect the results?
4. Can the model performance be improved?

## Conclusion
This project provides hands-on experience with building a decision tree model, training it on real-world data, and evaluating its performance. By answering the guided questions, users will better understand the mechanics of decision trees and how they perform on medical datasets.
