Predictive Analytics for Movie Success and Employee Retention
Welcome to the Predictive Analytics for Movie Success and Employee Retention project repository. This project aims to leverage machine learning techniques to predict the success of movies and forecast employee retention, providing valuable insights for informed decision-making.

Table of Contents
Introduction
Project Structure
Datasets
Installation
Usage
Results
Technologies
Contributors
License
Introduction
This project consists of two main parts:

Movie Success Prediction: Analyzing various factors such as genre, rating, and runtime to predict the success of movies with an accuracy of 98.8%.
Employee Retention Forecasting: Evaluating critical factors like commute distance, age, and monthly income to forecast employee attrition with 90% accuracy, enabling targeted retention strategies.
Project Structure
css
Copy code
Predictive-Analytics/
├── data/
│   ├── movie_dataset.csv
│   ├── employee_dataset.csv
├── notebooks/
│   ├── Movie_Success_Prediction.ipynb
│   ├── Employee_Retention_Prediction.ipynb
├── models/
│   ├── movie_success_model.pkl
│   ├── employee_retention_model.pkl
├── src/
│   ├── data_preprocessing.py
│   ├── model_training.py
│   ├── model_evaluation.py
├── README.md
├── requirements.txt
└── LICENSE
Datasets
Movie Dataset: Contains information about various movies including genre, rating, runtime, and other relevant features.
Employee Dataset: Includes details such as employee age, commute distance, monthly income, and other critical factors affecting retention.
Installation
Clone the repository:
bash
Copy code
git clone https://github.com/yourusername/Predictive-Analytics.git
Navigate to the project directory:
bash
Copy code
cd Predictive-Analytics
Install the required packages:
bash
Copy code
pip install -r requirements.txt
Usage
Movie Success Prediction:

Navigate to the notebooks directory and open the Movie_Success_Prediction.ipynb notebook.
Follow the steps in the notebook to preprocess the data, train the model, and evaluate its performance.
Employee Retention Prediction:

Navigate to the notebooks directory and open the Employee_Retention_Prediction.ipynb notebook.
Follow the steps in the notebook to preprocess the data, train the model, and evaluate its performance.
Results
Movie Success Prediction: Achieved an accuracy of 98.8% by analyzing key factors like genre, rating, and runtime.
Employee Retention Prediction: Achieved 90% accuracy in forecasting employee attrition by evaluating critical factors like commute distance, age, and monthly income. This led to targeted retention strategies that reduced attrition rates by 15%.
Technologies
Programming Languages: Python
Libraries and Frameworks: TensorFlow, Keras, Scikit-learn, Pandas, Numpy, Matplotlib
Tools: Jupyter Notebook, Git
Contributors
Sadhak Jain
License
This project is licensed under the MIT License. See the LICENSE file for details.
