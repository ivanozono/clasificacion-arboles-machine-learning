# 🌳 Classification with Decision Tree and Random Forest

This project demonstrates how to apply supervised classification models using **Decision Trees** and **Random Forest** with the classic **Iris** dataset, highlighting their interpretability and predictive value.

## 🎯 Project Objective

To predict the species of an iris flower based on morphological measurements using interpretable and robust models, applicable to real-world use cases across various industries.

---

## 🛠️ Technologies Used

- Python 3
- Scikit-learn
- Pandas
- Matplotlib / Seaborn
- Joblib

---

## 📊 Project Workflow

1. **Load the data** using the Iris dataset from `sklearn.datasets`.
2. **Split the data** into training and test sets.
3. Train a **Decision Tree** model.
4. Train a **Random Forest** model with 100 trees.
5. Evaluate both models using metrics such as accuracy, F1-score, etc.
6. **Visualize** the decision tree.
7. Analyze **feature importance** in the Random Forest.
8. Save and reload the trained model using `joblib`.

---

## 📁 Repository Structure
- clasificacion_arbol_random_forest.ipynb
- modelo_random_forest.pkl
- README.md
- requirements.txt

---

## 📌 Key Results

- The **Random Forest** achieved higher accuracy and generalization than the individual Decision Tree.
- The most important variables for species prediction were identified.
- The model was saved and can be deployed or reused without retraining.

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/your_username/clasificacion-arboles-machine-learning.git
```
2.	Install the dependencies:
```
pip install -r requirements.txt
```
3.	Open the notebook:
```
jupyter notebook clasificacion_arbol_random_forest.ipynb
```
📚 Credits

This project was developed in Google Colab as a demonstration exercise on supervised classification. Inspired by data science best practices applied to real-world problems.

⸻

## 🔄 Possible Improvements
	•	Use cross-validation and hyperparameter tuning.
	•	Apply the model to a real-world case (churn, fraud, scoring).
	•	Deploy as a microservice using FastAPI or Streamlit.
---

## 📝 Project Blog

You can read a more detailed explanation of the approach, algorithms, and technical decisions in the following article:

👉 [Decision Trees and Random Forest (Notion Blog)](https://wheat-pulsar-663.notion.site/Decision-Trees-y-Random-Forest-215f96ec2e1080e98e78d3c2b335ec9c)

Ideal for understanding the logic behind the code and its applications to real-world problems.
