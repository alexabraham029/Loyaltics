🧠 Loyaltics — Customer Churn Prediction using ANN
Loyaltics is a deep learning-powered churn prediction system that leverages an Artificial Neural Network (ANN) to analyze customer behavior and predict the likelihood of churn. The project helps businesses proactively identify and retain customers at risk of leaving.

Built with TensorFlow and trained on structured customer data, Loyaltics is designed to deliver accurate, real-time churn predictions through a clean and interactive interface.

📌 Features
🔍 Predicts customer churn with high accuracy using ANN

🧼 End-to-end data preprocessing (encoding, scaling)

📊 Model evaluation with accuracy, precision, recall, confusion matrix

🎯 Simple interface for live predictions using Streamlit

💡 Ideal for telecom, banking, or subscription-based businesses

📁 Dataset
This project uses a customer dataset with the following features:

Credit Score

Geography

Gender

Age

Tenure

Balance

Number of Products

Has Credit Card

Is Active Member

Estimated Salary

Target variable: Exited

1 = Customer churned

0 = Customer retained

🧠 ANN Architecture
Input Layer: 11 neurons (one for each feature)

Hidden Layers: 2 fully connected layers (ReLU activation)

Output Layer: 1 neuron (Sigmoid activation)

Loss Function: Binary Crossentropy

Optimizer: Adam

⚙️ Tech Stack
Python 3.10+

TensorFlow / Keras

NumPy, Pandas

Scikit-learn

Matplotlib / Seaborn (for EDA)

Streamlit (for UI deployment)

🚀 Getting Started
Clone the repository

bash
Copy
Edit
git clone https://github.com/alexabraham029/loyaltics.git
cd loyaltics
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
Run the app

bash
Copy
Edit
streamlit run app.py
📈 Sample Results
Test Accuracy: ~85%

Confusion Matrix, Precision & Recall for balanced insights

Easily extendable to more complex models like XGBoost or ensemble techniques

📬 Contact
For collaboration, questions, or suggestions, feel free to reach out via:

GitHub: @alexabraham029

Email: alexabraham029@gmail.com

Let me know if you’d like a version with screenshots, model performance plots, or deployment instructions for platforms like Heroku or Hugging Face Spaces.
