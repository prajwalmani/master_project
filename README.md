# Master Project
Name:Prajwal Mani  
Email Id:pbm6@njit.edu  
Subject Code:CS700B  
Professor: Dr. Jason T. L. Wang  

### This readme file talks about how to run the ccsc tools 
### Installing python:
* Python 3.8.6: (https://www.python.org/downloads/release/python-386/

#### Creatinng virtunal enviornment 
```
python -m venv <env name>
```
To activate the env  
```
.\<env name>\Scripts\activate
```
#### Creating virtual enviornment using conda based environment.yaml file 
```
conda env create -f environment.yml
```
#### Installing Python Packages using pip  
We use the below command to install a python package through the terminal 
```
pip install <package-name>
```

In a scenario where there is multiple working on a projects or if we are testing some one else project we usually have requirements.txt where we list all the packages required to run the project successfully we use the below command
```
pip install -r requirements.txt 
```

#### Installing Python Packages using conda 
```
conda install <package-name>
```

Note: Please add the py enviornment/conda enviornment to the jupyter notebook before running the notebook  
#### Adding enviornment to ipykernal

You can add the conda env has ipykernal by using the below command line 
 ```
 python -m ipykernel install --user --name < py/conda env name>

 ```
 

Note: Please virtunal environments so there wont be any packages version errors while executing the tools 

### SolarUnet-magnetic-tracking
Zenodo link:https://zenodo.org/record/5643647#.Y5pJEnbMJPZ  
Github link:https://github.com/ccsc-tools/SolarUnet-magnetic-tracking  

Python version: 3.8.6
The requirements are already setup for you using conda enviornment.yml 



