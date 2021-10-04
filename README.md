C:\Users\hvijay\AppData\Local\Continuum\anaconda3
Create ENV

''' bash
conda create -n wineq python=3.7 -y
'''

Activate ENV

''' bash
conda activate wineq 
'''

create a REQ file
install the req file 
''' bash
pip install -r req.tzt
'''

git init

dvc init 

dvc add data_given/winequality.csv

git commit -m "first commit"
git branch -M main
git push -u origin main