create env

```bash
  conda create -n wineq python=3.9 -y
```

activate env

```bash
  conda activate wineq
```
create a requirements.txt

install the req.txt
```bash
pip install -r requirements.txt
```
download the data from

https://drive.google.com/drive/folders/18zqQiCJVgF7uzXgfbIJ-04zgz1ItNfF5?usp=sharing

```bash
git init
```
'''bash
dvc init
```
```bash
dvc add data_given/winequality.csv
```
```bash
git add .
```
```bash
git commit -m "First Commit"
```

One liner update for Readme
```bash
git add . ; git commit -m "Updated README.md"
```
git remote add origin https://github.com/Chandu-Pudhipattu/MLOPS_sample_dvc_app.git
git branch -M main
git push -u origin main

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

setup commands
```bash
# local pkg install
pip install -e .
```

build your own package commands -
```bash
python setup.py sdist bdist_wheel
```
```bash
heroku deployment
```

Running on Gunicorn
```bash
web: gunicorn app:app
```

