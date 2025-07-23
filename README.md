# Employee Salary Prediction

An interactive web application built with Streamlit that uses a Gradient Boosting Classifier to predict whether an individual's income is over or under 50k.

🚀 Features
Single Prediction: Enter an individual's details into a simple form to get an instant salary prediction.

Batch Prediction: Upload a CSV file containing multiple records and get predictions for all of them at once.

Interactive Visualizations: View prediction results and confidence scores through interactive Plotly pie charts.

Download Results: Download the batch prediction results as a new CSV file with a single click.

Responsive Design: The UI is fully responsive and works seamlessly on desktop and mobile.

Theme Aware: Supports both light and dark modes for a comfortable user experience.

High-Performance Model: Powered by a GradientBoostingClassifier tuned with GridSearchCV for high accuracy.

📸 Screenshots
![SCRIPT](https://github.com/user-attachments/assets/7cc71ad9-a7b9-4189-a986-03da2df090a5)
![VISULAZATIONBOXPLOT](https://github.com/user-attachments/assets/e33d4101-c5a8-428b-aeac-a6ed53458fc3)
![ACCURACY SCRIPT](https://github.com/user-attachments/assets/6b4a8e3b-e161-47d3-8daf-6307c364d028)
![ACCURACY OF MODEL HEATMAP](https://github.com/user-attachments/assets/2e6924e3-cab6-43ae-873b-5528398f0c6f)
![STREMLETHOMEPAGE](https://github.com/user-attachments/assets/33e97bbc-1627-4ca8-b193-e676df7df211)
![MAINPAGE](https://github.com/user-attachments/assets/6d871c8b-afa1-41b0-b4d9-3827449396fd)
![HTMLPAGE](https://github.com/user-attachments/assets/22e644f2-84f3-436f-8040-ef70712b0dd5)




🛠️ Technology Stack
Backend & ML: Python

Web Framework: Streamlit,Flask

Machine Learning: Scikit-learn

Data Manipulation: Pandas, NumPy

Data Visualization: Plotly, Seaborn, Matplotlib

Model Persistence: Joblib

⚙️ Setup and Installation
Follow these steps to set up the project on your local machine.

1. Clone the Repository
git clone https://github.com/waleedul3/Employee-Salary-Prediction-Md-Waleedul-Haque.git
cd Employee-Salary-Prediction-Md-Waleedul-Haque

3. Create a Virtual Environment (Recommended)
It's highly recommended to create a virtual environment to manage project dependencies.

# For Windows
python -m venv venv
venv\Scripts\activate

# For macOS/Linux
python3 -m venv venv
source venv/bin/activate

3. Install Required Libraries
Install all the necessary libraries using the requirements.txt file.

pip install -r requirements.txt

▶️ How to Run the Application
Once the setup is complete, you can run the Streamlit application with a single command:

streamlit run app.py

Your web browser will automatically open a new tab with the running application.

🧠 Model Training
The machine learning model was trained using the "Adult.csv" dataset from the UCI Machine Learning Repository. The process involved:

Data Cleaning: Handling missing values.

Feature Engineering: Creating an experience feature from age.

Preprocessing: Scaling numerical features and one-hot encoding categorical features.

Hyperparameter Tuning: Using GridSearchCV to find the optimal parameters for the GradientBoostingClassifier.

Serialization: The final, trained pipeline was saved to the best_salary_model_pipeline.pkl file.

🌟 Future Scope
Cloud Deployment: Deploy the app to a public cloud platform like Streamlit Community Cloud or AWS.

Model Explainability: Integrate SHAP or LIME to explain model predictions.

Automated Retraining: Set up a CI/CD pipeline for automatic model retraining.

📜 License
This project is licensed under the MIT License. See the LICENSE file for details.
https://github.com/waleedul3/Employee-Salary-Prediction-Md-Waleedul-Haque/blob/0ee54528a96becc9030080ffa18e2c089f0b557a/LICENSE
