# Feature-Selection-techniques

## Filter Methods
Features are selected on the basis of their scores in various statistical tests for their correlation with the outcome variable. 
- Pearson correlation: For continuous features
- Chi square test: For categorical features
- ANOVA: For continuous features
- LDA: For categorical features
## Wrapper Methods
Use a subset of features and train a model using them. Based on the inferences that we draw from the previous model, we decide to add or remove features from your subset.
- Forward Selection
- Backward Elimination
- Recursive Feature elimination
## Embedded Methods
Embedded methods combine the qualities of filter and wrapper methods. It’s implemented by algorithms that have their own built-in feature selection methods.
- Lasso Regression
- Ridge Regression

## Other Methods
- Correlation Matrix Heatmap
- Feature Importance (Tree based models)
- PCA (Dimensionality Reduction)
- Pair plot
