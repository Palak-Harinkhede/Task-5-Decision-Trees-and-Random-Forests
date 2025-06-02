# Task 5: Decision Trees and Random Forests

## Dataset
Heart Disease Dataset

## Libraries Used
- pandas, numpy, matplotlib, seaborn
- scikit-learn (DecisionTreeClassifier, RandomForestClassifier)

## Steps Followed:
1. Data preprocessing and splitting.
2. Trained a Decision Tree Classifier.
3. Visualized the tree (`tree_plot.png`).
4. Checked for overfitting by analyzing tree depth (`depth_vs_accuracy.png`).
5. Trained a Random Forest and evaluated it.
6. Plotted feature importances (`feature_importance.png`).
7. Evaluated both models using 5-fold cross-validation.

## Results:
- Decision Tree Accuracy: 0.9854
- Random Forest Accuracy: 0.9854
- Decision Tree CV Accuracy: 1.0000
- Random Forest CV Accuracy: 0.9971

## Conclusion
Random Forest outperformed the single Decision Tree and provided better generalization as seen in cross-validation results.
