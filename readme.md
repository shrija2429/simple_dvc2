"create envi"
    create conda -n wineq2 pyhton 3.7 -y
"activate enviroment"
   conda activate
"created requirements.txt file"
"install the req"
   pip install -r requirements.txt

"download data" 
https://drive.google.com/drive/folders/18zqQiCJVgF7uzXgfbIJ-04zgz1ItNfF5?usp=sharing
winequality.csv

git init

dvc init

dvc add data_given/winequality.csv

git add .
git commit -m "first commit"
