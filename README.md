# Women-Clothing-E-Commerce-Analysis-using-Machine-Learning

# Data Source:
The dataset used is from Women's E-Commerce Clothing Reviews. It contains 10 variables and 23,486 rows, which provide detailed customer reviews, allowing for machine learning analysis to predict customer sentiment and preferences.

# Workflow:
## Data Cleaning:

Removal of irrelevant columns and handling missing values. Rows with insignificant amounts of data were deleted to improve the quality of the dataset.
## Feature Engineering:

Categorical variables were converted into numerical representations using one-hot encoding. This was done to ensure that machine learning algorithms could process the data accurately.
## Modeling:

Three models were used: Random Forest, Decision Tree, and AdaBoost. Each model was trained and evaluated using accuracy, precision, recall, and F1 score metrics.
## Evaluation:

The models were compared, showing that Random Forest had the highest performance with an F1 score of 0.79. However, overfitting was observed in some models, indicating potential imbalances in the data.
# Data Visualization:
Various visualizations were used, including:

1. Correlation Heatmap: To explore relationships between variables.
2. Pie Charts: Showcasing the distribution of customer ratings.
3. Box Plots: Highlighting relationships between ratings and review text length.

# Conclusion:
The study shows that Random Forest performed best in predicting customer preferences from e-commerce reviews. However, model improvements could be achieved by addressing data imbalances and further tuning hyperparameters. This analysis helps retailers better understand customer feedback and improve product offerings.
