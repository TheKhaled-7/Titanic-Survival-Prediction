# Titanic-Survival-Prediction

<img width="1271" height="693" alt="Screenshot 2025-07-30 025722" src="https://github.com/user-attachments/assets/803ee6fe-fb8f-4976-9d2e-bba3c01c3fe8" />

Welcome to the Titanic Survival Prediction project! 🌟 This Jupyter Notebook (Titanic.ipynb) takes you on an exciting journey through the famous Titanic dataset, aiming to predict whether passengers survived the historic voyage. Using the power of Python 🐍, we explore, preprocess, and build a predictive model with a sprinkle of data science magic! The notebook loads the dataset with pandas, performs exploratory data analysis 📊, and trains a logistic regression model to predict survival based on features like Pclass, Sex, Age, and Fare. Plus, it includes a cool sample prediction for a new passenger! 😎
Features:

📂 Loads and dives into the Titanic dataset (train.csv).
🔧 Preprocesses data by encoding Sex (male/female) and selecting key features.
🧠 Trains a logistic regression model to predict survival (0 or 1).
📈 Evaluates the model with an accuracy score (~82.68% on the test set).
✨ Makes a sample prediction for a new passenger with custom inputs.

Dataset:

The dataset is the iconic Titanic train.csv, packed with passenger info like PassengerId, Survived, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, and Embarked. It’s a treasure trove for data enthusiasts! 🗝️
How to Run:

Make sure you have Python and the required libraries (pandas, numpy, matplotlib, seaborn, scikit-learn) installed. 🛠️
Clone this repo and open Titanic.ipynb in Jupyter Notebook.
Place train.csv in the same directory as the notebook.
Run the cells step-by-step to explore the data, train the model, and predict survival! 🚀

Results:

The logistic regression model shines with an accuracy of ~82.68% on the test set! 🎉 A sample prediction shows how the model handles new data, making it super practical.
Future Improvements:

🧹 Handle missing values (like Age and Cabin) with smarter imputation.
🔍 Experiment with feature engineering or add more features for better predictions.
⚙️ Try advanced algorithms like Random Forest or XGBoost for a performance boost.
