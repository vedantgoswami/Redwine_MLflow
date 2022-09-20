create env
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

git init

dvc init

dvc add data_given/winequality-red.csv

git add .

git commit -m "first commit"
