# Covid19-Psychological-Impact-Prediction 🧠😷

**Covid19-Psychological-Impact-Prediction** is a machine learning and Flask web app project that analyzes the mental health impact of the COVID-19 pandemic and predicts psychological outcomes such as stress, anxiety, and depression based on user inputs. The project includes data cleaning, exploratory data analysis (EDA), feature engineering, and training a classification model using scikit-learn. A user-friendly web interface is built using Flask, where individuals can input relevant information (e.g., age, gender, isolation status, job impact, etc.) to get predictions about their potential mental health condition during the pandemic. This tool aims to raise awareness and offer a basic risk assessment that could help individuals and health professionals take proactive measures.

## 🔍 Key Features

- Cleaned and analyzed real-world mental health survey data related to COVID-19  
- Built a classification model using logistic regression / decision tree / other ML algorithm  
- Addressed class imbalance and evaluated the model using accuracy, precision, recall, and F1-score  
- Developed a Flask web app for real-time predictions based on user input  
- Helps in identifying people at high psychological risk during the pandemic

## 🛠️ Technologies Used

- Python  
- pandas, NumPy  
- seaborn, matplotlib  
- scikit-learn  
- Flask  
- HTML/CSS (for front-end templates)

## 📁 Project Structure

Covid19-Psychological-Impact-Prediction/
├── app.py # Flask app script
├── model.pkl # Trained ML model
├── templates/ # HTML templates for the web app
│ └── index.html
├── static/ # CSS or images (if any)
├── data/ # Dataset used
├── notebooks/ # Jupyter notebooks for EDA and modeling
├── requirements.txt # Required Python packages
└── README.md # Project documentation


## 🚀 How to Run the Project

1. Clone the repository:  
   `git clone https://github.com/Nandana-pramod/Covid19-Psychological-Impact-Prediction.git`

2. Navigate to the project folder:  
   `cd Covid19-Psychological-Impact-Prediction`

3. Create and activate a virtual environment (optional but recommended):  
   `python -m venv venv`  
   `source venv/bin/activate` (or `venv\Scripts\activate` on Windows)

4. Install the required dependencies:  
   `pip install -r requirements.txt`

5. Run the Flask app:  
   `python app.py`

6. Open your browser and go to:  
   `http://127.0.0.1:5000`

## 📌 Next Steps

- Improve model performance using ensemble methods (e.g., Random Forest, XGBoost)  
- Add visual feedback to the web interface  
- Deploy the application using services like Heroku or Render  
- Add multilingual support for broader accessibility


