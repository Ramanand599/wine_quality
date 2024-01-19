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