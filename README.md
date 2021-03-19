create env
'''bash
conda create -n Simple app python=3.7 -y

activate env
'''bash
conda activate Simple app

created req file

install req
'''bash 
pip install -r requirements.txt
'''
download data from https://drive.google.com/drive/folders/1xw0XX-WK74uxtFFLySbtnX-ODdmdK5Ec

git init

dvc init

dvc add data_given/winequality.csv

git add .
git commit -m "first commit"