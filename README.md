create enviroment
```bash
conda create -n wineq python=3.9 -y
```
activate enviroment
```bash
conda activate wineq
```
create a requirements file
```bash
type nul > requirements.txt 
```
install requirements
```bash
pip install -r requirements.txt
```

```bash
Download the data from:https://drive.google.com/drive/folders/1xw0XX-WK74uxtFFLySbtnX-ODdmdK5Ec
```
```bash
git init
```
```bash
dvc init
dvc add data_given/winequality.csv
```
```bash
git add . && git commit -m "first commit"
```
```bash
git remote add origin https://github.com/<USERNAME>/<REPO NAME>.git
git branch -M main
git push -u origin main
```
After Completing train and evaluate
```bash
dvc repro
```
```bash
dvc params diff
```
```bash
dvc metrics show
```
```bash
dvc metrics diff
```

For prediction
install library manualy
```bash
pip install pytest
pip install tox
```
or 
```bash
pip install requirements.txt
```

tox command -
```bash
tox
```
for rebuilding -
```bash
tox -r
```
pytest command
```bash
pytest -v
```
setup commands -
```bash
pip install -e .
```

build your own package command -
```bash
python setup.py sdist wheel
```
