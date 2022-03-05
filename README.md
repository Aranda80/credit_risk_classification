![Credit Risk Classification](Images/credit_risk.png)

# Credit Risk Classification

Credit risk poses a classification problem that’s inherently imbalanced. This is because healthy loans easily outnumber risky loans. In this application, we’ll use various techniques to train and evaluate models with imbalanced classes. We’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

## Steps taken to produce the analysis

    1- Split the Data into Training and Testing Sets

    2- Create a Logistic Regression Model with the Original Data by: 
        - instantiating the logistic regression model, 
        - scaling the data, 
        - fitting the model, and 
        - predicting the data.

    3- Predict a Logistic Regression Model with Resampled Training Data by:
        - instantiating the random oversampler model, 
        - fit the original training data to the random_oversampler model, 
        - instantiating the logistic regression model, 
        - scaling the resampled data, 
        - fitting the model with the scaled resampled data, and 
        - predicting the data.


## OUTCOME: Credit Risk Analysis Report

Use the `credit_risk_report.md` file to read the report with the outcome of the analysis.

## Tecnologies required and installation guide:

* **imbalance-learn**

``` conda install -c conda-forge imbalanced-learn```

* **PyDotPlus**

``` conda install -c conda-forge pydotplus ```


## Instructions

Use the `credit_risk_resampling.ipynb` notebook to analyze the credit risk classification.


## Contributors

Jaime Aranda


---

## License

Licensed under the MIT License.
