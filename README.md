## ML FLoe experiments 

ml_flow tracking = https://dagshub.com/ninjalp/ml_flow_project.mlflow
import dagshub
dagshub.init(repo_owner='ninjalp', repo_name='ml_flow_project', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)


