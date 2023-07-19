# Enhancing Clinical Guidelines through the Integration of SKLearn Decision Trees for the Diagnosis of Diabetes Mellitus Type 2 🩺
### Project Artificial Intelligence in Health @ Vrije Universiteit Amsterdam 🎓

A joint work of **Kirandeep Gill** and **Mark Bartos** made for the Year 2 class of **Project Artificial Intelligence in Health**.

## About the Research Paper 📑

**Abstract**
This research explores using decision tree learning and clinical guidelines to optimize the diagnosis of Diabetes Mellitus Type 2 (DM-2) in adults. Two datasets from India and Germany were used, focusing on lifestyle and clinical measurements. SKLearn's Decision Tree Classifier with K-Fold Cross Validation was employed.

**Results**
Decision Tree 1 identified regular medicine and high blood pressure as significant factors for DM-2, with a slight contribution from family history. Decision Tree 2 found glucose levels and BMI most influential. Clinical guidelines missed sleep and prediabetes in the analysis.

**Conclusion**
Decision trees and clinical guidelines aligned on BMI, glucose, insulin, pregnancies, and blood pressure. However, they differed on sleep, prediabetes, and overlooked symptoms like thirst and weight loss.

## About the Code-Base and the Decision Trees 🧑‍💻
*📝 The code-bade is made avaliable for grading purposes.*

This repository uses the SKLearn library to perform a Decision Tree Classifier for the diagnosis of Diabetes Mellitus Type 2 (DM-2). Here's a brief overview of the steps:
1. Import the necessary libraries (Pandas, NumPy, SKLearn).
2. Load the dataset from 'dataset1_imp.csv' and 'dataset2_imp.csv' using Pandas.
3. Separate numerical and categorical columns for further processing.
4. Apply One-Hot Encoding to the categorical columns.
5. Combine the numerical and encoded categorical columns to create the processed DataFrame.
6. Prepare for K-Fold Cross Validation with 5 and 10 folds.
7. Train the Decision Tree Classifier with the specified maximum depth and criterion.
8. Evaluate the model using accuracy as the metric for each fold.
9. Visualize the decision tree using Graphviz.

**💡 A more detailed description over the modelling choices are avaliable in the Research Paper.**

## Visualized Results 📊

![Decision Tree 1](https://github.com/mrkbrts/vu-paih-group6/blob/6816141a23a9ccd0f96499dd187ccc7f06fbc1ea/Trees/tree1_age%20removed.png)
Decision Tree 1, based on Dataset 1 which focuses more on lifestyle choices

![Decision Tree 2](https://github.com/mrkbrts/vu-paih-group6/blob/6816141a23a9ccd0f96499dd187ccc7f06fbc1ea/Trees/tree2_age%20removed.png)
Decision Tree 2, based on Dataset 2 which focuses more on clinical measurements

## Acknowledgments

We would like to express our gratitude to the following sources for providing the datasets used in this project:

1. Neha Prerna Tigga and Dr. Shruti Garg of the Department of Computer Science and Engineering, BIT Mesra, Ranchi-835215, for making their dataset available for research and non-commercial purposes. For more information and proper citation of this dataset, please refer to the following publication:
Tigga, N. P., & Garg, S. (2020). Prediction of Type 2 Diabetes using Machine Learning Classification Methods. Procedia Computer Science, 167, 706-716. DOI: https://doi.org/10.1016/j.procs.2020.03.336.
2. Daanouni, O., Cherradi, B., & Tmiri, A. (2019, October). Predicting diabetes diseases using mixed data and supervised machine learning algorithms. In Proceedings of the 4th International Conference on Smart City Applications (pp. 1-6).

We acknowledge the hard work and valuable contributions of the authors in collecting and preparing these datasets, which significantly contributed to the success of this project.
