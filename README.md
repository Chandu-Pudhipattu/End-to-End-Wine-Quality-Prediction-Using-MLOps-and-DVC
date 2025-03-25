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

git init

dvc init

dvc add data_given/winequality.csv

git add .

git commit -m "First Commit"

One liner update for Readme
```bash
git add . ; git commit -m "Updated README.md"
```
git remote add origin https://github.com/Chandu-Pudhipattu/MLOPS_sample_dvc_app.git
git branch -M main
git push -u origin main
