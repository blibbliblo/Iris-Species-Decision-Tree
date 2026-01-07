# Custom Decision Tree Classifier for Iris Dataset

Project Overview
This project implements a Decision Tree classifier from scratch using Python and applies it to the classic Iris dataset. The goal is to understand the fundamental mechanics of decision trees, including concepts like entropy and information gain, and to evaluate their performance on a well-known classification problem. The project also covers data loading, preprocessing, model training, evaluation, and visualization of both the data and the decision tree structure.

Features
- **Custom Decision Tree Implementation**: A complete implementation of a Decision Tree classifier, including `Node` and `DecisionTree` classes
- **Entropy and Information Gain**: Core concepts of decision tree learning are implemented for splitting criteria
- **Data Loading**: Utilizes `kagglehub` to download and load the Iris dataset
- **Data Preprocessing**: Data is prepared for model training, including splitting into training and testing sets
- **Model Training & Evaluation**: The custom Decision Tree is trained and evaluated for accuracy
- **Data Visualization**: Exploratory Data Analysis (EDA) is performed through pair plots to understand feature distributions and relationships
- **Decision Tree Visualization**: The trained decision tree structure is visualized both textually and graphically using `graphviz`

Dataset
 - The project uses the **Iris dataset**, a multivariate dataset introduced by the British statistician and biologist Ronald Fisher in 1936. The dataset consists of 150 samples from three species of Iris (Iris setosa, Iris    virginica, and Iris versicolor), with four features measured from each sample: the length and the width of the sepals and petals.

Results
 - The custom Decision Tree achieved an accuracy of approximately **96.67%** on the test set, demonstrating its effectiveness in classifying Iris species
 - Visualizations provided insights into feature distributions and the decision-making logic of the trained model

Conclusion
 - This project successfully demonstrates the implementation and application of a custom Decision Tree classifier. It provides a hands-on understanding of how these powerful algorithms work, from data splitting criteria to    final class predictions, and how to effectively visualize their structure and performance
