**This is my project for the ML exam.**

**The Goal**: In this project, you will take the role of a data scientist in an insurance company. Your task is to build a machine learning model able to predict the severity of a crash, that is useful to embed into the pricing of an insurance policy.

***The Goal in a nutshell***: Binary Classification, <span style="color:green"> 0 = Low Intensity Crash </span>  whereas <span style="color:red"> 1 = High intensity Crash.</span>

**In this code you'll find**:
1) **Exploratory Data Analysis**, also with Sweetviz and y-pandas profiling
2) **Data Cleaning and Feature engineering**
3) **Nested vs Stratified K-fold Cross Validation**
4) **GridSearch vs Optuna** for Hyperparameter tuning/optimization
5) **Models**
   - 5a) ***Lasso Logistic Regression***
   - 5b) ***Random Forest***
   - 5c) ***AdaBoost***
   - 5d) ***Gradient Boosting***
   - 5e) ***XGBOOST***
   - 5f) ***CATBOOST***
6) **Shap vs Lime** for model explainability and features importance
7) **Writing efficient code: Pipeline**
<br>

**Long story Short:** Picking the best model is a tough task and requires a thoroughly examination of hyperparameter tuning/optimization, model assumptions, data structure and data prepocessing, evaluation of generalized metrics and much more. That is may not has been carried out extensively and in NOT soat manner in this project, therefore final conclusion are always relative. Yet, the best model, that maximize ***recall***, is **CATBOOST**. 
The finding is underpinned by the distribution plot of the prediction of each model, Confusion matrices, Overfitting assessment and the fact that the majority of features were categorical.

