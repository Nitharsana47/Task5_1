Project Objective
To analyze employee-related data using Decision Tree and Random Forest classifiers, evaluate their performance, visualize the decision-making process, control model complexity, and interpret key features affecting predictions.

1. Trained a Decision Tree Classifier
*Built and trained a DecisionTreeClassifier.
*Visualized the tree structure to understand decision logic.
*Controlled depth to avoid overfitting (max_depth, min_samples_split).

2. Controlled Overfitting
*Compared model performance for different tree depths.
*Identified best depth that balances training and test accuracy.

3. Trained a Random Forest Classifier
*Built a RandomForestClassifier with multiple trees.
*Compared accuracy against Decision Tree.
*Achieved better generalization with ensemble method.

4. Interpreted Feature Importances
*Extracted and visualized important features influencing model predictions.
*Used bar charts to present top influencing features.

5. Evaluated Using Cross-Validation
*Applied 5-fold cross-validation to assess model performance.
*Reported average accuracy and ensured model reliability.

Model	Test Accuracy	Cross-Validation Avg
Random Forest CV Accuracy: ≈ 0.997
Decision Tree CV Accuracy: ≈ 0.985

Random Forest performed better in both accuracy and stability.



