## Reference
- A Complete Machine Learning Project Walk-Through in Python
    - https://github.com/WillKoehrsen/machine-learning-project-walkthrough
    - http://www.nyc.gov/html/gbee/downloads/misc/nyc_benchmarking_disclosure_data_definitions_2017.pdf



## Objective
    The objective is to use the energy data to build a model that can predict the Energy Star Score of a building and interpret the results to find the factors which influence the score.

    What is Energy Star Score?
    - A 1-to-100 percentile ranking based on self-reported energy usage for the reporting year. The Energy Star score is a relative measure used for comparing the energy efficiency of buildings.


## Steps
1. Data cleaning and formatting
    - convert data type
    - dealing with missing values.
    - remove outliers
    
2. Exploratory data analysis
3. Feature engineering and selection
4. Compare several machine learning models on a performance metric
5. Perform hyperparameter tuning on the best model
6. Evaluate the best model on the testing set
7. Interpret the model results
8. Draw conclusions and document work


## Setup python env
```
virtualenv --system-site-packages -p python3 venv3

. venv3/bin/activate

(venv3) pip3 install -r requirements.txt

...
(venv3) deactivate

```

