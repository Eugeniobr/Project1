# Data Scientist Nanodegree - Project1

## Project motivation

This is the first project of the Udacity Data Scientist Nanodegree. In this project, I analyzed
the 2019 StackOverflow survey dataset with the objective of answering a few questions.

## Installation 

This project was implemented in Python 3.6 and made use of the following python libraries:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [scikit-learn](http://scikit-learn.org/stable/)
- [Matplotlib](https://matplotlib.org/)

## Files

- project_1_nb.ipynb: jupyter notebook that contains the analysis of the dataset.  
- survey_results_.zip: compressed file that contains survey_results_public.csv and survey_results_public.csv.  
- survey_results_public.csv: CSV file that contains the information provided by the survey participants.  
- survey_results_schema.csv: CSV file that contains information about the columns of survey_results_public.csv.  

### Run

In a terminal or command window, navigate to the top-level project directory `Project1/` and run the following command:  
```jupyter notebook project_1_nb.ipynb```

### Summary results 

Based on the analysis I performed, the following conclusions can be drawn:
1. Programmer who get paid more tend to visit StackOverflow less.
2. There’s no relationship between working remotely and salary variables.
3. There’s no relationship between age and job satisfaction variables.
4. The linear regression model built using only numeric features doesn’t perfom well in predicting salary.

### Acknowledgements

The 2019 StackOverflow dataset is openly acessible and can be found on this [link](https://insights.stackoverflow.com/survey).
