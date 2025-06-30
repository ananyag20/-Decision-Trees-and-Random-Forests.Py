Task 5: Decision Tree and Random Forest - Heart Disease Dataset
 Objective
To learn tree-based models for classification using Decision Trees and Random Forests, and analyze their performance.

## Dataset
- **Heart Disease Dataset**
- Path used: `C:\Users\anany\Downloads\archive (2)\heart.csv`

## Tools Used
- Python
- Scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn

## Tasks Completed
1. Loaded and explored the dataset
2. Trained a Decision Tree and visualized it
3. Analyzed overfitting and pruned the tree using `max_depth`
4. Trained a Random Forest model and compared accuracy
5. Evaluated models using classification report, confusion matrix
6. Calculated and plotted feature importances
7. Used 5-fold cross-validation to assess model stability

## Results
- **Decision Tree Accuracy**: ~75%
- **Pruned Tree Accuracy**: ~80%
- **Random Forest Accuracy**: ~85%
- **Top Features**: `cp`, `thalach`, `exang`, `oldpeak`

## Conclusion
Random Forest outperformed the Decision Tree in terms of accuracy and generalization. Feature importance provided insights into key predictors of heart disease.

## How to Run
Make sure to adjust the file path if your dataset is in a different location.

