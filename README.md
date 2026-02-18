<h1 align="center">📱 Mobile Device Usage & User Behavior Classification</h1>

<p align="center">
  <b>End-to-End Machine Learning Project</b><br>
  Predicting smartphone dependency levels using behavioral analytics
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python">
  <img src="https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikit-learn">
  <img src="https://img.shields.io/badge/Type-Multi--Class%20Classification-green">
  <img src="https://img.shields.io/badge/Status-Completed-success">
</p>

---

<h2>🚀 Project Overview</h2>

<p>
This project builds a <b>multi-class classification model</b> to predict smartphone user behavior levels 
based on structured mobile usage metrics.
</p>

<p>
Using a dataset of <b>700 users</b>, the model classifies individuals into five behavioral categories 
ranging from casual users to power users.
</p>

---

<h2>🎯 Business Objective</h2>

<ul>
  <li>Analyze smartphone usage patterns</li>
  <li>Segment users based on device dependency</li>
  <li>Predict behavioral class (1–5)</li>
  <li>Evaluate model performance using classification metrics</li>
</ul>

---

<h2>🧠 Target Classes</h2>

<table>
  <tr>
    <th>Class</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>1</td>
    <td>Casual User</td>
  </tr>
  <tr>
    <td>2–4</td>
    <td>Moderate / Active User</td>
  </tr>
  <tr>
    <td>5</td>
    <td>Heavy / Power User</td>
  </tr>
</table>

---

<h2>🏗️ Machine Learning Pipeline</h2>

<h4>1️⃣ Data Preprocessing</h4>
<ul>
  <li>Train-test split</li>
  <li>Feature scaling</li>
  <li>Categorical encoding (ColumnTransformer)</li>
  <li>Pipeline integration</li>
</ul>

<h4>2️⃣ Model Development</h4>
<ul>
  <li>Logistic Regression</li>
  <li>Decision Tree</li>
  <li>Random Forest</li>
</ul>

<h4>3️⃣ Model Evaluation</h4>
<ul>
  <li>Accuracy</li>
  <li>Precision</li>
  <li>Recall</li>
  <li>F1-Score</li>
  <li>Confusion Matrix</li>
</ul>

---

<h2>📊 Key Insights</h2>

<ul>
  <li>Screen-On Time and App Usage Time are strong predictors.</li>
  <li>Tree-based models capture nonlinear patterns effectively.</li>
  <li>Pipeline structure ensures clean and reproducible workflows.</li>
</ul>

---

<h2>🛠️ Tech Stack</h2>

<p>
Python • Pandas • NumPy • Matplotlib • Seaborn • Scikit-learn
</p>

---

<h2>📂 Project Structure</h2>

<pre>
Mobile-User-Behavior-Classification/
│
├── ANNE_behaviour_Device.ipynb
├── user_behavior_dataset.csv
├── requirements.txt
└── README.md
</pre>

---

<h2>⚙️ Run Locally</h2>

<pre>
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
pip install -r requirements.txt
jupyter notebook
</pre>

---

<h2>🔮 Future Improvements</h2>

<ul>
  <li>Hyperparameter tuning (GridSearchCV)</li>
  <li>Cross-validation</li>
  <li>Model deployment (Flask / FastAPI)</li>
  <li>Interactive dashboard (Streamlit)</li>
</ul>

---
<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python">
  <img src="https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikit-learn">
  <img src="https://img.shields.io/badge/Type-Multi--Class%20Classification-green">
  <img src="https://img.shields.io/badge/Status-Active%20Development-brightgreen">
</p>

<p align="center">
  🚧 <b>This project is currently under active development.</b><br>
  New features, optimization, and deployment updates are in progress.
</p>
