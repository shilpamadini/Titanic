# Titanic
This folder contains the information for Titanic data analysis project. The data set and detailed information about the data can be found at [Kaggle](https://www.kaggle.com/c/titanic)

## Contents
  1. titanic_data_analysis.html
        - final report of the data analysis
  2. titanic_data_analysis.ipynb
        - master code for running the analysis
  2. titanic_data.csv
        - data set used for the analysis
  3. img
        - folder containing the images used in the final report
  4. environment.yaml
       - environment file for this project
  5. reveal.js
        - framework used to create HTML presentaions
        - can be downloaded from this [Github url](https://github.com/hakimel/reveal.js.git)
  6. README.md
        - simple documentation for this project and Installation
  7. titanic_data_exploration_test_code.ipynb
        - data exploration test code. Not used in the final analysis.

## Installation
please follow below instruction to create this project environment on your local desktop.
- download the project folder from the github url
 ```
git clone https://github.com/shilpamadini/titanic.git
```
- install the conda environment using the environment file. this will create a conda environment with the same name listed in the environment file. this will also install all the required packages for this project
```
conda env create -f environment.yaml
```
 - list the conda environments
 ```
 conda env list
 ```
 - activate the enviroment for titanic
 ```
 source activate titanic
 ```
 - activate jupyter notebook. this will open a webbrowser.By default, the notebook server runs at http://localhost:8888
 ```
 jupyter notebook
 ```
 - Open the master code file titanic_data_analysis.ipynb from the jupyter web browser. Happy coding!
 -
