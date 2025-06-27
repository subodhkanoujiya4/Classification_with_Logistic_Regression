##🧠 Logistic Regression - Binary Classification
This project implements a binary classifier using Logistic Regression to detect whether a tumor is Malignant (M) or Benign (B) using the Breast Cancer Wisconsin Dataset.

📁 Dataset
Source: data.csv
Samples: 569
Target: diagnosis (M = Malignant, B = Benign)
Features: 30 numeric features like radius_mean, texture_mean, etc.

🛠️ Tools & Libraries
Python
Pandas
NumPy
Scikit-learn
Matplotlib

🔄 Workflow
1️⃣ Data Preprocessing
Dropped irrelevant columns (id, Unnamed: 32)
Encoded diagnosis: M → 1, B → 0
Scaled features using StandardScaler
2️⃣ Model Training
Split dataset: 80% training / 20% testing
Trained Logistic Regression using sklearn.linear_model.LogisticRegression
3️⃣ Evaluation Metrics
Confusion Matrix
Precision, Recall, F1-score
ROC Curve & AUC Score
4️⃣ Threshold Tuning
Demonstrated how changing the decision threshold affects classification
Plotted the Sigmoid function to explain probability output

🧪 Example Output
📊 Confusion Matrix

[[70  1]
 [ 2 41]]
📈 Classification Report
Class	Precision	Recall	F1-Score
Benign	0.97	0.99	0.98
Malignant	0.98	0.95	0.96

🔍 ROC-AUC Score: 0.997
📊 Visualizations
ROC Curve: Measures classifier performance
Sigmoid Function: Maps linear model output to probability (0–1)

🚀 How to Run

# Step 1: Clone the repo or copy files
git clone https://github.com/yourusername/logistic-regression-breast-cancer.git
cd logistic-regression-breast-cancer

# Step 2: Install dependencies
pip install pandas numpy scikit-learn matplotlib

# Step 3: Run the Python file or Notebook
python logistic_regression.py
# OR open logistic_regression.ipynb in Jupyter
Ensure data.csv is in the same folder.

📂 Project Structure

📁 logistic-regression-breast-cancer
 ┣ 📄 data.csv
 ┣ 📄 logistic_regression.py
 ┣ 📄 logistic_regression.ipynb
 ┗ 📄 README.md
 
👨‍💻 Author
Subodh Kanoujiya
LinkedIn | GitHub
