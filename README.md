# Deep Classifier project

# workflow

1. Update config.yaml
2. Update secrets.yaml [Optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in scr config
6. Update the components
7. Update the pipeline
8. Test run the pipeline stage
9. Run tox for testing your package
10. Update the dvc.yaml
11. Run "dvc repro" for running all the stages in pipeline

STEP 1: Set the env variable | Get it from dagshub -> remote tab -> mlflow tab

MLFLOW_TRACKING_URI=https://dagshub.com/VaheC/CNN_Classifier.mlflow
MLFLOW_TRACKING_USERNAME=VaheC
MLFLOW_TRACKING_PASSWORD=<> \

STEP 2: install mlflow

STEP 3: Set remote URI

STEP 4: Use context manager of mlflow to start run and then log metrics, params and model