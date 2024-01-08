create env
'''bash
conda create -n wineq python=3.7 -y'''

activate env
'''bash
conda activate wineq'''

create a req file
'''bash
pip install -r rquirements.txt'''

git init
dvc init
dvcadd data_given/winequality.csv
git add .
git commit