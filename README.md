Create Environment
```bash
conda create -n wineq python=3.7 -y
```
activate env
```bash
conda activate wineq
```
created a requirements file

install the requirements
```bash
pip install -r requirements.txt
```

download the data from 
https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009
```bash
git init
```

```bash
dvc init
```
```bash
dvc add data_given/winequality-red.csv
```
```bash
git add .
```
``` bash
git commit -m "first commit"
```
```bash
git add . && git commit -m "update Readme.md"
```
```bash
git remote add origin https://github.com/vedantgoswami/Redwine_MLflow.git
git branch -M main
git push origin main
```
tox command -
```bash
tox
```
for rebuilding -
```bash
tox -r
```
pytest command -
```bash
pytest -v 
```

setup commands -
```bash
pip install -e .
```

build your own package commands-
```commandline
python setup.py sdist bdist_wheel
```

create an artifacts folder


mlflow server command -

mlflow server \
    --backend-store-uri sqlite:///mlflow.db \
    --default-artifact-root ./artifacts \
    --host 0.0.0.0 -p 1234