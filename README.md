👉 **The Challenge**

The sinking of the Titanic is one of the most infamous shipwrecks in history.
On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.

While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.

In this challenge, we ask you to build a predictive model that answers the question: “what sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc).

**Titanic Survival Prediction using Logistic Regression**

Hello Everyone, 👋 

Here is My Classification Project based on Predicting Survival of Passenger using Logistic Regression.

- **Dataset**

I used Titanic Dataset avaliable on Kaggle.

📍**Link to Dataset :** [Titanic Dataset](https://www.kaggle.com/competitions/titanic/data?select=test.csv)

- **Steps involved in the Project**

1️⃣ **Data Cleaning**

Data Cleaning involves cleaning Different Columns of Dataset and removing anomalies present in the Dataset.

- Removing Null Values in the Age Columns and replacing them with Mean Age by using fillna().mean().

- Dropping Cabin Columns as it contains Many Null Values.

- Dropping Text Columns from our Dataset because our Model only works on Numerical Data.

- Creating Dummies Value for Sex Column and Converting it into a DataFrame and Concatenating it with Orignal DataFrame.

2️⃣ **Data Visualization**

Data Visualization involves visualizing Different Columns of Dataset and finding Relationship among them.

- Visualizing Number of People Survived and Not Survived by their Gender using sns.countplot().

- Visualizing Number of People's present in Different Age Group by using sns.histplot().

3️⃣ **Model Building**

I used Logistic Regression for this Problem as here we have to classify the Survival of Passengers.

- Firstly I have definied Dependent and Independent Variables for our Traning and Testing.

- I have splitted data into Traning and Testing by using Train Test Split.

- Then I fit the Model with X_train and y_train and checked the Score.

- And Finally I predicted the Result from our Trained Model.

📍**Link to Notebook :** [Titanic Survival Prediction using Logistic Regression](https://www.kaggle.com/code/themrityunjaypathak/titanic-survival-prediction)
