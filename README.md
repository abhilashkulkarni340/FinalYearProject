# FinalYearProject
Code for final year project

## Instructions for downloading virtual environment and loading the environment

Download Python 3.6.6

Check python version, it should be 3.6.6:

`$ python --version`

if it shows `python is not a command` the path variable hasn't been set. set the PATH variable.

Download python environment :

`$ pip install virtualenv`

Create virtual environment :

 `$ virtualenv project`
 
 Activate virtual environment :
 
 `$ project\Scripts\activate `
 
 (for macOS) `$ source project\bin\activate`
 
 Create the environment of the project :
 Move the requirements.txt file outside project folder and run :
 
 `$ pip install -r requirements.txt`
 
 Open Jupyter notebook containing the project :
 
`$ jupyter notebook "Model Implementation.ipynb"`

Closing the environment :

`$ project\Scripts\deactivate`

(for macOS) `$ deactivate`
