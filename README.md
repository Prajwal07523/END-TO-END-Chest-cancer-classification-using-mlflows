# End-to-End-Chest-Cancer-Classification-using-MLflow-DVC


## Workflows

1. Update config.yaml
2. Update secrets.yaml [Optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline 
8. Update the main.py
9. Update the dvc.yaml





## MLflow

- [Documentation](https://mlflow.org/docs/latest/index.html)

##### cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/Prajwal07523/END-TO-END-Chest-cancer-classification-using-mlflows.mlflow \
MLFLOW_TRACKING_USERNAME=Prajwal07523 \
MLFLOW_TRACKING_PASSWORD=eb670b0869830e6c07d1977e3f1fc35e3533e8e2 \
python script.py

Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/Prajwal07523/END-TO-END-Chest-cancer-classification-using-mlflows.mlflow

export MLFLOW_TRACKING_USERNAME=Prajwal07523

export MLFLOW_TRACKING_PASSWORD=eb670b0869830e6c07d1977e3f1fc35e3533e8e2

```