## Titanic Survival Prediction

Hello Everyone,

Here is My Classification Project based on Predicting Survival of Passengers using Logistic Regression.

## Dataset

I used Titanic Dataset avaliable on Kaggle.

**Link to the Dataset :** [Titanic Dataset](https://www.kaggle.com/competitions/titanic/data?select=test.csv)

## Problem Statement

- The sinking of the Titanic is one of the most infamous shipwrecks in history.

- On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg.

- Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.

- While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.

- In this challenge, we have to build a predictive model that answers the question : “what sorts of people were more likely to survive?” using Passenger Data.

## Table of Contents

- [Setting up the Enviroment](#setting-up-the-enviroment)
- [Libraries required for the Project](#libraries-required-for-the-project)
- [Getting started with Repository](#getting-started)
- [Steps involved in the Project](#steps-involved-in-the-project)
- [Conclusion](#conclusion)
- [Link to the Notebook](#link-to-the-notebook)

## Setting up the Enviroment

Jupyter Notebook is required for this project and you can install and set it up in the terminal.

- Install the Notebook
```
pip install notebook
```

- Run the Notebook
```
jupyter notebook
```

## Libraries required for the Project

**Pandas**

- Go to Terminal and run this Code
```
pip install pandas
```

- Go to Jupyter Notebook and run this Code from a Cell
```
!pip install pandas
```

**Matplotlib**

- Go to Terminal and run this Code
```
pip install matplotlib
```

- Go to Jupyter Notebook and run this Code from a Cell
```
!pip install matplotlib
```

**Seaborn**

- Go to Terminal and run this Code
```
pip install seaborn
```

- Go to Jupyter Notebook and run this Code from a Cell
```
!pip install seaborn
```

**Sklearn**

- Go to Terminal and run this Code
```
pip install -U scikit-learn
```

- Go to Jupyter Notebook and run this Code from a Cell
```
!pip install -U scikit-learn
```

## Getting Started

- Clone the repository to your local machine using the following command :
```
git clone https://github.com/TheMrityunjayPathak/TitanicSurvivalPrediction.git
```

## Steps involved in the Project

**Data Cleaning**

- Removing Null Values in the Age Columns and replacing them with Mean Age by using fillna().mean().

- Dropping Cabin Columns as it contains Many Null Values.

- Dropping Text Columns from our Dataset because our Model only works on Numerical Data.

- Creating Dummies Value for Sex Column and Converting it into a DataFrame and Concatenating it with Orignal DataFrame.

**Data Visualization**

- Visualizing Number of People Survived and Not Survived by their Gender using sns.countplot()

![download](https://github.com/TheMrityunjayPathak/TitanicSurvivalPrediction/assets/123563634/9e955743-52d5-4655-9a81-97421e7ddd84)

- Visualizing Number of People's present in Different Age Group by using sns.histplot()

![download](https://github.com/TheMrityunjayPathak/TitanicSurvivalPrediction/assets/123563634/cd218922-c0be-42f7-b50c-f5a1bea32ba5)

**Model Building**

- Firstly I have defined Dependent and Independent Variables for our Traning and Testing.

- I have splitted data into Traning and Testing Set by using Train Test Split.

- Then I Trained the Model with X_train and y_train and checked the Score.

- And Finally I predicted the Result from our Trained Model.

## Conclusion

- In conclusion, the Titanic Survival Prediction Project was an exciting endeavor where we applied logistic regression to predict the survival of passengers aboard the Titanic.

- Our model achieved a score of 0.79, indicating a reasonably good level of accuracy in predicting survival outcomes.

- Utilizing logistic regression as our chosen algorithm, we built a robust predictive model. Logistic regression allowed us to model the binary nature of the target variable survival or non-survival based on the selected features.

## Link to the Notebook
[Titanic Survival Prediction](https://www.kaggle.com/code/themrityunjaypathak/titanic-survival-prediction)

| [Scroll to Top ⬆️](#titanic-survival-prediction) |
|:---:|
