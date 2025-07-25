# titanic-survival
🚢 Titanic Survival Prediction using Decision Tree Classifier
This project demonstrates how to build a simple Decision Tree Classifier to predict survival outcomes of passengers on the Titanic using Python and Scikit-Learn.

📂 Dataset
The dataset used is the Titanic dataset, containing information such as:

Passenger demographics (Sex, Age, Pclass)

Ticket and fare details

Survival status

🛠️ Key Steps
Import Libraries:

pandas for data manipulation

scikit-learn for the machine learning model

Load Data:

Read titanic.csv using pd.read_csv()

Display the first few rows to understand the data structure

Data Preprocessing:

Encode Sex column (male → 1, female → 2)

Handle missing Age values by replacing them with the mean age

Model Building:

Use DecisionTreeClassifier from sklearn.tree

Split the data into training and test sets

Train the model using .fit()

Evaluate accuracy using .score() (~81% in this example)

Predict survival outcomes for test data

📈 Results
Achieved an accuracy score of ~81%.

Generated predictions to classify passengers as Survived or Not Survived.

📌 How to Run
Clone this repository or download the notebook.

Ensure you have pandas and scikit-learn installed:

bash
Copy
Edit
pip install pandas scikit-learn
Place the titanic.csv in your working directory.

Run the notebook step-by-step.

📚 Learning Outcome
✅ Data cleaning & preprocessing
✅ Feature encoding
✅ Handling missing values
✅ Implementing a decision tree model
✅ Evaluating model performance

🤝 Let’s Connect!
If you found this project helpful or have suggestions, feel free to connect on LinkedIn or fork this repo to experiment further.
