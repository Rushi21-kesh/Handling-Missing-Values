# Handling-Missing-Values
![image](https://user-images.githubusercontent.com/61430438/102975994-ea7bfc80-4526-11eb-8bb1-dd5e36fcef4e.png)

## Missing data, also known as missing values, is where some of the observations in a data set are blank.
ex. 
- At age feature womens hesitate to put down their age
- Men hesitate to show their salary
- informations are not that valid

### Type of data

    1. Categorical Data: 
        It is a string type of data such as Gender, Sex, education, etc.

    2. Discrite Data:
        It is a number type data which is whole number only such as How many bank account you have,How many bike you have, etc.

    3.Continous Data:
        It is a number type data such as Age, Height, Profit, etc.
    
### Different type of Missing data

    1. Missing Completely at Random (MCAR)
        - The variable is missing completely at random (MCAR) if the probability of being missing is the same for all the observations.
        - When data is MCAR, there is absolutely no relationship between the data missing and other values.

    2. Missing Data Not at Random (MNAR)
        - There is absolutely some relationship between the data misssing and any other feature's  values in dataset. 

    3. Missing at Random(MAR)
        - If the propensity for a data point to be missing is't related to the missing data, but it's related to some of the observed data.
        - When Data is MAR, The data is missing but can be predicted from other information.
    
## All techniques of handling Missing values

    1. Mean/Mode/Median replacement
    2. Random sample imputation
    3. Capturing NAN values with a new feature
    4. End of Distribution imputation
    5. Arbitrary imputation
    6. Frequent categories imputation   
#### Note we perform all this techniques on 'Titanic' dataset, you can download it from :
- [Titanic Datset](https://github.com/Rushi21-kesh/Handling-Missing-Values/blob/main/Titanic.csv)
