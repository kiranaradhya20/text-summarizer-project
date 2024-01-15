# text-summarizer-project

# Workflows

1. Update config.yaml
2. Update params.yaml
3. Update entity
4. Update the configuration manager in src config
5. update the conponents
6. update the pipeline
7. update the main.py
8. update the app.py

# How to run?
### STEPS:

Clone the repository

```bash
https://https://github.com/kiranaradhya20/text-summarizer-project
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n summary python=3.8 -y
```

```bash
conda activate summary
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```

```bash
# Finally run the following command
python app.py
```




## MLflow

- [Documentation](https://mlflow.org/docs/latest/index.html)

- [MLflow tutorial](https://youtube.com/playlist?list=PLkz_y24mlSJZrqiZ4_cLUiP0CBN5wFmTb&si=zEp_C8zLHt1DzWKK)

##### cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/kiranaradhya20/text-summarizer-project.mlflow \
MLFLOW_TRACKING_USERNAME=kiranaradhya20 \
MLFLOW_TRACKING_PASSWORD=15353351c9c000dec7bdda258e97a8d254a9233d \
python script.py

Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/kiranaradhya20/text-summarizer-project.mlflow 

export MLFLOW_TRACKING_USERNAME=kiranaradhya20 

export MLFLOW_TRACKING_PASSWORD=15353351c9c000dec7bdda258e97a8d254a9233d

```
### DVC cmd

1. dvc init
2. dvc repro
3. dvc dag


