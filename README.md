# [cScore Decision Making System (TEAM CL.HS)]

# About the project

- The main idea of the project: creating ML-model to predict borrower default rate
- Deadline: MVP - 22 days, Test - 4 days, Prod - 2 day
- Supported modules: SVM, Random Forest, Extreme Gradient Boosting, CatBoost
- Additional framework: Automatic Machine Learning framework (H2O)

## About the Team

- [@Yurii Skiter](https://github.com/yuragoit) Team Lead, Dev, QA
- [@Damask](https://github.com/contract_restriction) Scrum Master, Dev, QA
- [@Vitarus](https://github.com/contract_restriction) PM, Dev, QA

## Start the app in Jupiter notebook

> **Step 01** - Download the code from the GH-repository (using GIT) 

```bash
$ # Get the code
$ git clone https://github.com/yuragoit/cScoreDMS.git
$ cd cScoreDMS
```

> **Step 02** - Start the APP in `Jupiter notebook` using appropriate ipynb-file

# Code-base structure:
* data folder with datasets
* 00_Preprocessing.ipynb (EDA with Preprocessing)
* 01_AutoML_H2O.ipynb (Automatic Machine Learning framework, used for comparison with custom models)
* 02_Modeling.ipynb (Custom credit scoring model)

# About Dataset
1. Dataset is imbalanced
2. Data is non-linear
3. Dataset have outlier which is make-sense data (we not drop it)
4. Feature of dataset is almost everything was categorical type
5. Small Dataset

## Input Data
The dataset is **data_input.xlsx**
## Modeling results for Credit Scoring case
The model results are compiled in the **model_dms** binary file.


## Screenshots

![Distribustio](https://user-images.githubusercontent.com/101989870/220159715-1bfb0eca-ee7b-47df-8e9b-2373c5defa44.png)

![tSNE](https://user-images.githubusercontent.com/101989870/220159859-e50ae34c-99dc-439d-a5b4-2a4d2de41f5a.png)

## License

[MIT](https://choosealicense.com/licenses/mit/)

## Used By

This project is used by the company PJSC CL.HS