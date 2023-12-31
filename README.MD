# Project 1: Supervised Learning

__________________________________________________________

You can run this project by creating a conda environment and using Jupyter Notebook.  
There are two notebooks `covid_death_classification.ipynb` and `credit_score_classification.ipynb` for COVID Death classification and Credit Score classification cases.

# 1. Getting data
The Mexican COVID Death classification can be downloaded at https://www.kaggle.com/datasets/meirnizri/covid19-dataset?resource=download. The Credit Score classification dataset can be download at https://www.kaggle.com/datasets/parisrohan/credit-score-classification .  
  
The two datasets are also included in the data folder. In case it’s not included due to uploading limit, please do download the data from the web links provided above. And put the two dataset css files into `data` folder with correct name `credit_score_dataset.csv` and `covid_death_dataset.csv`. 

# 2. Run the notebook cases
To sucessfully run the code, first make sure you download or use the existing datasets under `data` folder with correct name `credit_score_dataset.csv` and `covid_death_dataset.csv`. 
 
## 2.1 Environment setup
1) Install Anaconda or miniconda from  
`https://docs.conda.io/en/latest/miniconda.html` 

2) Create conda environment by  
`conda create -n CS6741_SL python=3.8`
3) Then install libraries at project root by 
`pip install -r requirements.txt`  

Since the project only asked for analysis.pdf and RDADME.txt, Therefore, you can also install the python libraries by
`pip install pandas scikit-learn`  
`pip install xgboost`  
`pip install matplotlib`  
`pip install jupyter`   
`pip install ipykernel`   
`pip install scikit-learn-intelex`  

4) Add kernel to jupyter notebook by  
`python -m ipykernel install --user --name CS6741_SL`

## 2.2 Open jupyter notebook
1) Open jupyter notebook case
Open jupyter notebook from terminal by
`jupyter notebook`
2) Change kernel from Jupyter Notebook Menu Kernel/Change Kernel to CS6741_SL

## 2.3 Run through the notebook
There are two notebooks `covid_death_classification.ipynb` and `credit_score_classification.ipynb` for COVID Death classification and Credit Score classification cases.

You can simply use `run all` under menu `run` to run through each notebook. But be aware that, each notebook will run over 12 hours due to the size of the data. It will be especially slow for SVM and KNN for each case.
  
## 2.4 Run results
The results can be find in notebook for each cases. The result plots can also be found under result_plots folder. 


