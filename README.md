# this is my end to end project

# first initialize the git

```
git init
```

```
git add abc.txt
git add .
```
```
git commit -m "this is my first commit"
```

```

git pull

```

```
bash your_file_name.sh
```

```
python setup.py install
```

# another way you can mention -e . in your requirement file and you can run

```
pip install -r requirements.txt
```


## MLflow

[Documentation](https://mlflow.org/docs/latest/index.html)


##### local cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/kanojiasanchit01/FSDSMENDTOEND.mlflow \
MLFLOW_TRACKING_USERNAME=kanojiasanchit01 \
MLFLOW_TRACKING_PASSWORD=your_token \
python script.py

Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/kanojiasanchit01/FSDSMENDTOEND.mlflow \

export MLFLOW_TRACKING_USERNAME=kanojiasanchit01

export MLFLOW_TRACKING_PASSWORD=your_token

```


### DVC cmd
- dvc init
- dvc repro
- dvc dag

