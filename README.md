# Breast-Cancer-Classification-ML
We are going to create a model which can predict if a person has breast-cancer.


# Prerequisite
- Python 3.10
- Anaconda / conda

# Steps
- These are some steps we are going to follow as we code:
  - Run `conda create --prefix ./env numpy pandas scikit-learn matplotlib notebook` in Anaconda/conda prompt. (creates a virtual environment with all necessary packages installed)
  - run `conda activate path/to/env` to activate the virtual environment.
  - run `jupyter notebook` to open jupyter notebook.
  - Create a python notebook.
  - Import all the packages.
  - Import the Breast Cancer Data from `sklearn.datasets`.
  - Create a pandas Dataframe using the Breast Cancer Data.
  - Check if there are any datafields empty/null.
  - Split the Data into features and target sub sets (X & Y respectively).
  - Import and initiliaze the classification model from `sklearn.ensemble`.
  - Split the feature and target datasets into train and test dataset.
  - Fit/Train the model using the train dataset.
  - Evaluate the model.
  
  # Evaluation
- To Evaluate our model we use different methods. Scikit-learn provides us many methods  for Evaluation. Some which we are going to use are :
  - Default model score method `model.score()`. (Returns [Coefficient of Determination](http://www.investopedia.com/terms/c/coefficient-of-determination.asp "Coefficient of Determination"))
  - Cross Validation.
  - sklearn.metrics.accuracy_score 
  - ROC (Receiver operating characteristic) curve
  - Confusion matrix
    
**ROC Curve**

[![ROC_CURVE](https://ik.imagekit.io/43bd8tl1l5kl/ML_PROJECT_BC/roc_curve_mCW_bxKVH8.png?ik-sdk-version=javascript-1.4.3&updatedAt=1642843944751)](https://ik.imagekit.io/43bd8tl1l5kl/ML_PROJECT_BC/roc_curve_mCW_bxKVH8.png?ik-sdk-version=javascript-1.4.3&updatedAt=1642843944751)


**Perfect ROC Curve**

[![ROC_CURVE_PERFECT](https://ik.imagekit.io/43bd8tl1l5kl/ML_PROJECT_BC/roc_curve_perfect_THoXWO2tK.png?ik-sdk-version=javascript-1.4.3&updatedAt=1642843944774)](https://ik.imagekit.io/43bd8tl1l5kl/ML_PROJECT_BC/roc_curve_perfect_THoXWO2tK.png?ik-sdk-version=javascript-1.4.3&updatedAt=1642843944774)




