Titanic Survival Prediction 🚢⚓
Predicting passenger survival on the Titanic using machine learning models.

📌 Project Overview
This project applies various machine learning algorithms to predict survival rates of Titanic passengers based on different features such as age, gender, fare, and class.

📂 Repository Structure
Titanic-Survival-Prediction/
│── data/                  # Dataset storage
│── notebooks/             # Jupyter/Colab notebooks
│── src/                   # Python scripts for preprocessing & modeling
│── models/                # Saved trained models
│── results/               # Evaluation reports & metrics
│── README.md              # Project documentation
│── requirements.txt       # Dependencies list
⚙️ Installation & Setup
Clone the repository:

bash
git clone https://github.com/YourUsername/Titanic-Survival-Prediction.git
Navigate to the folder:

bash
cd Titanic-Survival-Prediction
Install dependencies:

bash
pip install -r requirements.txt
Run the Python script / Jupyter notebook:

bash
python src/main.py
OR open the notebook in Google Colab.

🚀 Model Training
The following ML models are used:

Logistic Regression

Decision Tree

Random Forest

Support Vector Machine (SVM)

Model Evaluation

Model	                  Accuracy	   Precision	   Recall	      F1-Score
Logistic Regression     	1.00	      1.00	        1.00	        1.00
Decision Tree           	1.00       	1.00        	1.00	        1.00
Random Forest	            1.00	      1.00	        1.00	        1.00
SVM	                      0.988      	1.00	        0.971	        0.985

Random Forest, Decision Tree, and Logistic Regression performed perfectly, achieving 100% accuracy on the test set.

Confusion Matrix
[[50  0]
 [ 0 34]]


🔎 Visualizations

Countplot:Survival Count Distribution

Barplot: Survival by Gender

Scatterplot: Fare vs Age

🔗 Resources & References
Titanic Dataset - Kaggle
