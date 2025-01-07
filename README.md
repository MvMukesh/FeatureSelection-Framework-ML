<div align="center"> 
&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://www.linkedin.com/in/mukesh-manral/"><img src="https://img.shields.io/badge/LinkedIn-411AFF?style=for-the-badge&logo=LinkedIn&logoColor=white" /></a>  
&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://www.kaggle.com/mukeshmanral"><img src="https://img.shields.io/badge/Kaggle-411AFF?style=for-the-badge&logo=Kaggle&logoColor=white" /></a>
&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://medium.com/@manralai/lists"><img src="https://img.shields.io/badge/Medium-411AFF?style=for-the-badge&logo=Medium&logoColor=white" /></a>
&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://www.youtube.com/@manralai"><img src="https://img.shields.io/badge/Youtube-411AFF?style=for-the-badge&logo=Youtube&logoColor=white" /></a>
&nbsp;&nbsp;&nbsp;&nbsp; 
<a href="https://www.instagram.com/manralai/"><img src="https://img.shields.io/badge/Instagram-411AFF?style=for-the-badge&logo=Instagram&logoColor=white" /></a>
</div>

# FeatureSelection-Framework-ML

[![GitHub Issues](https://img.shields.io/github/issues/MvMukesh/FeatureSelection-Framework-ML.svg) ![GitHub followers](https://img.shields.io/github/followers/MvMukesh.svg?style=social\&label=Follow\&maxAge=2592000)](https://github.com/MvMukesh?tab=followers) [![GitHub forks](https://img.shields.io/github/forks/MvMukesh/FeatureSelection-Framework-ML.svg?style=social\&label=Fork\&maxAge=2592000)](https://github.com/MvMukesh/FeatureSelection-Framework-ML/network/) [![GitHub stars](https://img.shields.io/github/stars/MvMukesh/FeatureSelection-Framework-ML.svg?style=social\&label=Star\&maxAge=2592000)](https://github.com/MvMukesh/FeatureSelection-Framework-ML/stargazers/)


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
---

### How to make Features selection part of Pipeline ????
Feature Selection can be the part of Pipeline, but it is good to select Feature ahead before building pipeline and make the list of selected features part of the pipeline we want to deploy.

---

| Feature Selection Method | Nature            | Pros       | Cons |
|--------------------------|-----------------|------------|--------|
| `Filter Methods`           |Independent of ML Algorithm <br> Based only on variable characteristics | Quick Feature Removal <br> Model Agnostic <br> Fast Computation| Does not capture redundancy <br> Does not capture feature interaction <br> Poor model performance |
| `Wrapper Methods` / Greedy Algorithms          |Consider ML Algorithm <br> Evaluates subsets/grop of Features | Considers feature interaction <br> Best performance <br> Best feature subset for a given algorithm | Not model agnostic(features they find may not be best for certain algorithm) <br> Computation expensive <br> Often impracticable |
| `Embedded Methods`        |Feature selection during training of ML algorithm | Good model performance <br> Capture feature interaction <br> Better than Filter <br> Faster than Wrapper | Not model agnostic |

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
  
  
<div align="center"> 
&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://www.linkedin.com/in/mukesh-manral/"><img src="https://img.shields.io/badge/LinkedIn-411AFF?style=for-the-badge&logo=LinkedIn&logoColor=white" /></a>  
&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://www.kaggle.com/mukeshmanral"><img src="https://img.shields.io/badge/Kaggle-411AFF?style=for-the-badge&logo=Kaggle&logoColor=white" /></a>
&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://medium.com/@manralai/lists"><img src="https://img.shields.io/badge/Medium-411AFF?style=for-the-badge&logo=Medium&logoColor=white" /></a>
&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://www.youtube.com/@manralai"><img src="https://img.shields.io/badge/Youtube-411AFF?style=for-the-badge&logo=Youtube&logoColor=white" /></a>
&nbsp;&nbsp;&nbsp;&nbsp; 
<a href="https://www.instagram.com/manralai/"><img src="https://img.shields.io/badge/Instagram-411AFF?style=for-the-badge&logo=Instagram&logoColor=white" /></a>
</div> 
