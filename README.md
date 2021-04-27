# Data_masking
## Linear Algebra project from Practicum by Yandex

### Goals

- Develop a data transforming algorithm  for the Sure Tomorrow insurance company that would make it hard to recover personal information from the transformed data;
- Prove that the algorithm works correctly; 
- The data should be protected in such a way that the quality of machine learning models doesn't suffer.

### This project's repo includes the following files:

- The project's jupyter notebook (Data_masking.ipynb);
- A pdf format of the notebook (Data_masking.pdf);
- Input data (insurance_us.csv);
- Project description from Practicum (LA_project_description.pdf).

### This project includes the following steps:

1. Descriptive statistics;
2. Data Preprocessing: column names convertion, duplicates removal, data type chage;
3. Theoretical proof based on the equation of linear regression that the quality of a model doesn't change if we mask features;
4. Linear regression implementation;
5. Data preparation: invertibility testing;
6. Algorithm testing.

### Based on the analysis we have come to the following conclusions:

We have tested the algorithm and came to the following conclusion: all 4 models resulted in approximately the same R2 metric value. It means that our data masking technique and our implementation of the linear regression didn't change the quality of the model.


### The logbook of this project can be found [here](https://docs.google.com/spreadsheets/d/1SrGdReexaSEomJGS6yR6cRwJtHA_XqpprnLaE7B6Ayg/edit#gid=924050647) (Linear Algebra tab).
Total time spent on the project: 5.6 hours with a daily average of 1.88 hours working for 3 days.
