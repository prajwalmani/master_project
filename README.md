# Master Project
Name:Prajwal Mani  
Email Id:pbm6@njit.edu  
Subject Code:CS700B  
Professor: Dr. Jason T. L. Wang  

### This readme file talks about how to run the ccsc tools 
### Installing python:
* Python 3.8.6: https://www.python.org/downloads/release/python-386/
* Python 3.9.7: https://www.python.org/downloads/release/python-397/

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
Note: The requirements.txt and environemt.yaml will be in the code folder please check it out and use which one is avaible.
Note: Please virtunal environments so there wont be any packages version errors while executing the tools 

### SolarUnet-magnetic-tracking
Zenodo link:https://zenodo.org/record/5643647#.Y5pJEnbMJPZ  
Github link:https://github.com/ccsc-tools/SolarUnet-magnetic-tracking  

Python version: 3.8.6  
The requirements are already setup for you using conda enviornment.yml 

Note: Please follow the above steps to install conda env 

### FlareML
Zenodo link:https://zenodo.org/record/5634114#.Y5pSYnbMJPZ   
Github link:https://github.com/ccsc-tools/FlareML

Python version: 3.8.6  
The requirements are already setup for you using conda enviornment.yml 

Note: Please follow the above steps to install conda env 

### RNN-CME-prediction
Zenodo link:https://zenodo.org/record/7415731#.Y5pXo3bMJPZ   
Github link:https://github.com/ccsc-tools/RNN-CME-prediction

Python version: 3.9.7 
The requirements are already setup for you please use the requirements.txt

Note: Please follow the above steps to install from requirements.txt

### LSTM-flare-prediction
Zenodo link:https://zenodo.org/record/5739321#.Y5pYtXbMJPZ  
Github link:https://github.com/ccsc-tools/LSTM-flare-prediction

Python version: 3.8.6
The requirements are already setup for you using conda enviornment.yml 

Note: Please follow the above steps to install conda env 

### SEP-prediction
Zenodo link:https://zenodo.org/record/6757855#.Y5pZ4nbMJPY  
Github link:https://github.com/ccsc-tools/SEP-prediction

Python version: 3.9.7 
The requirements are already setup for you using conda enviornment.yml 

Note: Please follow the above steps to install conda env 

### Dst-prediction
Zenodo link:https://zenodo.org/record/6757855#.Y5pZ4nbMJPY  
Github link:https://github.com/ccsc-tools/Dst-prediction 

Python version: 3.9.7 
The requirements are already setup for you using conda enviornment.yml 

Note: Please follow the above steps to install conda env 

### TSInet-irradiance-reconstruction
Zenodo link:https://zenodo.org/record/7402229#.Y5pa53bMJPZ    
Github link:https://github.com/ccsc-tools/TSInet-irradiance-reconstruction

Python version: 3.8.6
The requirements are already setup for you using conda enviornment.yml 

Note: Please follow the above steps to install conda env 

### Kp-prediction

Zenodo link:https://zenodo.org/record/7120692#.Y5pbk3bMJPY  
Github link:https://github.com/ccsc-tools/Kp-prediction


Python version: 3.9.7
The requirements are already setup for you using conda enviornment.yml 

Note: Please follow the above steps to install conda env 



### CMETNet


Zenodo link:https://zenodo.org/record/7320334#.Y5pb-nbMJPY   
Github link:https://github.com/ccsc-tools/
Cuda Installation Package: You may download and install Cuda v 10.1 from https://developer.nvidia.com/cuda-10.1-download-archive-base

Python version: 3.8.6
The requirements are already setup for you using conda enviornment.yml 

Note: Please follow the above steps to install conda env 
