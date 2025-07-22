# MLP_with_MLflow

import dagshub
dagshub.init(repo_owner='sauravk8400', repo_name='MLP_with_MLflow', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)