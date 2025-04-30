# 🌸 Iris Flower Classification Project – ML Model Deployment with Flask

**📌 Project Summary**

This project focuses on building a machine learning model to classify iris flowers into three species: Setosa, Versicolor, and Virginica, based on four input features:

Sepal Length (cm)

Sepal Width (cm)

Petal Length (cm)

Petal Width (cm)

The final deployed app allows users to input these measurements via a web interface and get real-time predictions using the trained model. The application is built using Flask for the backend and HTML/CSS for the frontend.

**🚀 Project Workflow**

**1. Data Collection**

Used the classic Iris dataset from sklearn.datasets, which contains 150 samples equally divided among three classes.

**2. Data Preprocessing**

Checked for missing/null values (none found).

Visualized using pairplots and histograms to understand feature distributions.

Performed Label Encoding on the target column (species).

**3. Model Training**

Features: sepal length, sepal width, petal length, petal width

**Target: species**

Split data: 80% train / 20% test

Algorithms tried:

Logistic Regression

Decision Tree

K-Nearest Neighbors (KNN)

**Final Model: Logistic Regression**

Achieved **~97%** accuracy on test data.

**4. Model Evaluation**

Used accuracy, confusion matrix, and classification report.

Found that Logistic Regression performed best with minimal misclassification.

**5. Model Saving**

Saved the trained model using joblib.

**6. Flask Web App**

Created a web form for users to enter flower features.

Sent data to Flask backend where the model predicts the flower type.

Rendered the prediction on the results page.

Added input validation and styling with CSS for a smooth UI/UX.

**7. Deployment**

Tested locally using Flask.

(Optional) Can be deployed on platforms like Render, Heroku, or Vercel.

**🛠️ Technologies Used**

Python

Scikit-learn

Pandas, NumPy

Matplotlib, Seaborn (for EDA)

Flask

HTML5, CSS3

joblib (for model serialization)
```
📁 Project Structure

iris-classifier/
│
├── static/                  # (optional) for images/css
├── templates/
│   └── index.html           # Frontend UI
├── iris_model.pkl           # Saved model
├── app.py                   # Flask application
├── iris_model_training.ipynb# Model training notebook
├── requirements.txt         # Required packages
└── README.md                # Project overview
```
## 🖼️ Screenshots

![screenshot_2025-04-30_09-32-05](https://github.com/user-attachments/assets/b54aa4e1-63f4-48ce-9923-bb5e46afe630)
![screenshot_2025-04-30_09-32-58](https://github.com/user-attachments/assets/fbeefe98-ab7f-414f-bdfd-7d8b92693a39)
![screenshot_2025-04-30_09-33-30](https://github.com/user-attachments/assets/b384c72f-dbce-4a3c-a710-745b82e5412f)

## 🛠️ How to Run

```

git clone https://github.com/Mazid2003/IRIS-FLOWER-CLASSIFICATION-a-Data-Science-Project.git

cd Iris

pip install -r requirements.txt

python app.py

```

**📬 Contact**

Created by Mohammad Mazid

**💬 Want to Collaborate?**

Feel free to fork the repo, submit PRs, and give your feedback! 🔥💡

**📜 License**

This project is open-source under the MIT License. Feel free to use and modify it! 🚀
