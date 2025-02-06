# IS_6812_MSBA_Practice_Capstone

## If Cloning Project From GitHub Repository

This project relies on data obtained from [Kaggle](https://www.kaggle.com/competitions/home-credit-default-risk/data). In order to run the notebook, the data must be downloaded and saved to a directory named "data" in the same directory this README file and the python notebook are located.
 
## Questions and notes

- Q: In the EDA Assignment when we're exploring the target and predictors, are we supposed to look at all the predictors in all of the files (i.e. join the tables) or just the predictors in the application file?
    - A: We don't have to, but it's the bread and butter of the Kaggle competition! it will take the project to the next level.
    - Note: when working with the transactional data, it will have to be aggregated somehow so that there's just one row per applicant.

- Q: some columns have a lot of missing data, specifically predictive columsn. How do we solve this?
    - Bin the numeric data, transforming it into a categorical variable. For missing variables, that's just another category.
    - We can also use imputation, filling missing values with a measure of center or using a random forest or k-nearest neighbor model trained on a random sample of the data
    

