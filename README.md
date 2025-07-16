# DECISION-TREE-IMPLEMENTATION
COMPANY: CODTECH IT SOLUTIONS
NAME: MADANIKA PITTAM
INTERN ID: CT04DG1969
DOMAIN: MACHINE LEARNING
DURATION: 4 WEEKS
MENTOR: NEELA SANTOSH
Overview
This project aims to implement a Decision Tree Classifier using Scikit-learn to classify the species of iris flowers based on their physical characteristics. The task is a classic example of supervised machine learning, where the goal is to build a model that can learn from labeled data and accurately predict the class (species) of new, unseen samples.

The decision tree is a simple yet powerful algorithm that works by recursively splitting the data based on feature values to arrive at a decision. The model is intuitive, easy to visualize, and suitable for both classification and regression tasks.

 Dataset Description
The dataset used is the Iris flower dataset, which is one of the most well-known and widely used datasets in the field of machine learning. It was introduced by the British biologist and statistician Ronald Fisher in 1936.

The dataset contains 150 rows, each representing an iris flower with the following four features (all numerical):

Sepal length (in cm)

Sepal width (in cm)

Petal length (in cm)

Petal width (in cm)

There are three species (target classes):

Setosa (label 0)

Versicolor (label 1)

Virginica (label 2)

The dataset is perfectly balanced with 50 samples for each class, making it ideal for classification tasks.

Methodology
1. Importing Libraries
Python libraries such as NumPy, Pandas, Matplotlib, and Scikit-learn were used. Scikit-learn offers a built-in method to load the Iris dataset, making it easy to access without external files.

2. Data Exploration
After loading the dataset, the features and target values were separated. A sample of the dataset was displayed to understand the structure. The target classes and corresponding names were printed to verify the class labels.

3. Data Splitting
The dataset was split into training (80%) and testing (20%) sets using the train_test_split function. This helps in evaluating the model’s ability to generalize to unseen data. A random seed (random_state=42) was used to ensure consistent results.

4. Model Building
A DecisionTreeClassifier was initialized and trained on the training data using the fit() method. The model learns to split the dataset into subsets based on feature values to best separate the target classes.

5. Tree Visualization
The tree was visualized using plot_tree() from Scikit-learn. The decision tree diagram clearly shows the hierarchical decision-making structure:

Internal nodes represent feature-based conditions.

Leaf nodes represent final classifications.

Colors indicate different classes.

Feature importance is visually apparent, helping interpret model behavior.

6. Model Evaluation
Predictions were made on the test set using the predict() method. The performance was evaluated using:

Accuracy Score: Proportion of correct predictions.

Classification Report: Precision, recall, and F1-score for each class.

The model achieved a very high accuracy, indicating that it effectively classified most test samples. This is expected since the Iris dataset is well-structured and linearly separable, which suits decision tree learning.
Key Insights and Analysis
The decision tree model was highly accurate and simple to interpret.

Features such as petal length and petal width played a significant role in decision-making, as reflected in the tree visualization.

The model demonstrates how a decision tree uses simple thresholds to split data and reach a classification.

While decision trees are easy to visualize and explain, they can become complex and overfit when data is noisy or high-dimensional. In this case, however, the model was well-behaved due to the clean nature of the Iris dataset.
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/13567c6a-87f8-4088-8521-69a4e06f2d21" />
