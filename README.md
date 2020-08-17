This is a version of ASKCOS modified to work with synthesis planning code for multiple molecules. The main change is a modification of the condition prediction model to allow for returning each entity separately, instead of grouping solvents and reagents together, respectively.

Tested with python 3.5

required packages (without specification, the packages are installed using conda install directly):
pymongo
six
tqdm
keras==2.2.4
theano==1.0.4
tensorflow==1.13.1
celery
sklearn
matplotlib
rdkit==2018.03.3
django

