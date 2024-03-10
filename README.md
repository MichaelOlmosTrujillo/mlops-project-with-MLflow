# mlops-project-with-MLflow

## Workflows

1. Update config.yaml
2. Update schema.yaml
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline
8. Update the main.py
9. Update the app.py


# How to run?

### STEPS

Clone the repository

```bash
https://github.com/MichaelOlmosTrujillo/mlops-project-with-MLflow
```
### STEP 01 - create a conda environment after opening the repository

```bash
virtualenv mlops_project_env
```

### STEP 03 - install the requirements
```bash
pip install -r requirements.txt
```

```bash
# Finally run the following command
python app.y
```
Now, 
```bash
open up your local host and port
```


## ML flow

[Documentation](https://mlflow.org/docs/latest/index.html)

#### cmd
-mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/MichaelOlmosTrujillo/mlops-project-with-MLflow.mlflow \
MLFLOW_TRACKING_USERNAME=MichaelOlmosTrujillo \
MLFLOW_TRACKING_PASSWORD=601bc70d3a3a608a786aeea37536435b511f4b94 \
python script.py

Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/MichaelOlmosTrujillo/mlops-project-with-MLflow.mlflow 
export MLFLOW_TRACKING_USERNAME=MichaelOlmosTrujillo
export MLFLOW_TRACKING_PASSWORD=601bc70d3a3a608a786aeea37536435b511f4b94
```

