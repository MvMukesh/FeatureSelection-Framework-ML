# FeatureSelection-Framework-ML
Answer of how to select variables in data set and build simpler, faster, more reliable and interpretable machine learning models

---
### Why Do we Select Features?
* Easier to implement by software developers --> Model Production
* Enhance generalisation by reducing overfitting
* Reduced risk of data errors during model use
* Simple model are easier to interpret
* Short training time
* Data redundancy
---
### Why?? Reducing Features for Model Deployment
* Smaller json messages sent over to the model
  * Json messages contain only necessary variables / inputs
* Less lines of code for error handling
  * Error handlers need to be written for each variable / input
* Less feature engineering code
* Less information to log

<hr>
<p align="center">
  <img src="https://user-images.githubusercontent.com/26667491/221222048-042bff14-e7f4-4173-9f72-af723c5dee3c.gif" height='300' width='700'/>
  
<p align="center">
  <kbd><img src="https://user-images.githubusercontent.com/26667491/221211426-ad4fa8ec-e8cc-46c1-8c8f-74608f5f4289.png" height='400' width='1000'/> </kbd>
  

1. `Feature Selection Methods`
  * Filter Methods
    * Variance 
    * Correlation
    * Univariate Selection
  * Wrapper Methods
    * Forward Feature Selection
    * Backword Feature Elemenation
    * Exaustive Search
  * Embedded / Hybrid Methods
    * LASSO
    * Tree Importance
  * Moving Forward

| Feature Selection Method | Nature            | Pros       | Cons |
|--------------------------|-----------------|------------|--------|
| `Filter Methods`           |Independent of ML Algorithm <br> Based only on variable characteristics | Quick Feature Removal <br> Model Agnostic <br> Fast Computation| Does not capture redundancy <br> Does not capture feature interaction <br> Poor model performance |
| `Wrapper Methods` / Greedy Algorithms          |Consider ML Algorithm <br> Evaluates subsets/grop of Features | Considers feature interaction <br> Best performance <br> Best feature subset for a given algorithm | Not model agnostic <br> Computation expensive <br> Often impracticable |
| `mbedded Methods `        | | | |

| Feature Selection Methods | Code + Blog Link| Video Link |
|------------------------------------|-----------------|------------|
| | | |
| | | |
| | | |
 
 2. Feature Selection -- `Basic Methods`
   
  * Removing 
    * Constant Features
    * Quasi-Constant Features
    * Duplicated Features

| Feature Selection -- Basic Methods | Code + Blog Link| Video Link |
|------------------------------------|-----------------|------------|
| | | |
| | | |
| | | |


3. Feature Selection -- `Correlation`

  * Removing Correlated Features
  * Basic Selection Methods + Correlation -> Pipeline

| Feature Selection -- Correlation | Code + Blog Link| Video Link |
|------------------------------------|-----------------|------------|
| | | |
| | | |
| | | |

## `Filter Methods`
4. `Univariate Statistical Methods`
  * Mutual Information
  * Chi-square distribution
  * Anova
  * Basic Selection Methods + Statistical Methods -> Pipeline

| Univariate Statistical Methods -- Filter Method | Code + Blog Link| Video Link |
|-------------------------------------------------|-----------------|------------|
| | | |
| | | |
| | | |
  
5. `Other Methods and Metrics`
  * Univariate ROC-AUC, MSE etc
  * Method used in a KDD competition - 2009
  
## `Wrapper Methods`
6. `Wrapper Methods`
  * Forward Feature Selection
  * Backward Feature Selection
  * Exhaustive Feature Selection
  
| Wrapper Methods -- Feature Selection| Code + Blog Link| Video Link |
|-------------------------------------|-----------------|------------|
| | | |
| | | |
| | | |
 
## `Embedded Methods`
7. `Linear Model Coefficients` 
  * Logistic Regression Coefficients
  * Linear Regression Coefficients
  * Effect of Regularization on Coefficients
  * Basic Selection Methods + Correlation + Embedded -> Pipeline

| Linear Model Coefficients| Code + Blog Link| Video Link |
|--------------------------|-----------------|------------|
| | | |
| | | |
| | | |
  
8. `Lasso`
  * Lasso
  * Basic Selection Methods + Correlation + Lasso -> Pipeline

| Lasso| Code + Blog Link| Video Link |
|------|-----------------|------------|
| | | |
| | | |
| | | |
  
9. `Tree Importance`
  * Random Forest derived Feature Importance
  * Tree importance + Recursive Feature Elimination
  * Basic Selection Methods + Correlation + Tree importance -> Pipeline 
  
| Tree Importance| Code + Blog Link| Video Link |
|----------------|-----------------|------------|
| | | |
| | | |
| | | |
 
## `Hybrid Methods`
10. `Hybrid Methods`
  * Feature Shuffling
  * Recursive Feature Elimination
  * Recursive Feature Addition
  
| Hybrid Methods| Code + Blog Link| Video Link |
|----------------|-----------------|------------|
| | | |
| | | |
| | | |  
  
  
  
