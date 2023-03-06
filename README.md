# :running_woman: Predict customer churn using XGBoost :running_man:

In this project, we use XGBoost to build a collection of boosted trees, and use
continuous and categorical data from the [IBM Base Samples](https://www.ibm.com/docs/en/cognos-analytics/11.1.0?topic=samples-base)
to predict whether or not a customer will stop using a company's service. It is
often more expensive to acquire new customers than to retain existing ones. For this reason, large corporations are seeking to develop models to predict which customers are more likely to change and take actions accordingly.

## Setting up the Python environment

The following command is required to run the Flask app.

```
pipenv install --ignore-pipfile
```

## File description

[A Jupyter notebook is provided in the notebooks folder notebooks/XGBoost\_on\_Telco\_customer\_churn.ipynb](notebooks/XGBoost_on_Telco_customer_churn.ipynb), which provides detailed steps on the model building.
[There are two pickled files stored in folder
app\_flask/artifacts/telco\_customer\_churn](app_flask/artifacts/telco_customer_churn), one for the trained model and
other one for the preprocessing pipeline. Those pickled files are needed for
the model deployment.

## Running the Flask app

When everything is set up properly, running the Flask app can be done using the
following command.

```
python app_flask/app.py
```
