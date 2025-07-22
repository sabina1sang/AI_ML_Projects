# 🧠 MNIST Digit Classifier — Neural Network from Scratch (NumPy)

This project demonstrates my understanding of neural networks by implementing a digit classifier using only **NumPy** and **manual backpropagation**. I trained it on the MNIST dataset and stored predictions in a **SQLite database**. This was done without using any high-level machine learning frameworks like TensorFlow or PyTorch.

---

## 📌 Objective

To showcase a **hands-on implementation of a neural network** — from architecture to training loop — proving a deep understanding of:
- Linear algebra
- Activation functions
- Gradient descent
- Weight updates
- Data flow (forward + backward propagation)

---

## 🚀 What This Project Includes

- A fully functional **feedforward neural network**, written from scratch
- Training on **handwritten digit images** (MNIST dataset)
- Custom implementation of:
  - Sigmoid activation
  - Manual gradient descent
  - Manual loss calculation (MSE)
- SQLite integration to **log predictions for further use**
- Visualizations of **training loss and accuracy**

---

## 🏗️ Tech Stack

| Purpose        | Tool/Library       |
|----------------|--------------------|
| Data           | `keras.datasets.mnist` |
| Core Logic     | `NumPy`            |
| Visualization  | `Matplotlib`       |
| Storage        | `SQLite3` (Python built-in) |
| Notebook       | Jupyter / VS Code  |

---

## 📊 Results (After Training 1000 Epochs on 1000 Samples)

- Accuracy: ~90% (on training subset)
- Visualized graphs of loss and accuracy across epochs
- Predictions stored in `database.db` with inputs and predicted labels

---

## 🗂️ Files Included

myproject/
├── Neural_net.ipynb # Main training and evaluation notebook
├── Database_view.ipynb # Optional: view stored predictions from SQLite
├── database.db # SQLite database with predictions
├── requirements.txt # Dependencies
└── .gitignore # Ignored cache/virtual env files


---

## 🔧 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/sabina1sang/AI_ML_Projects.git
   cd AI_ML_Projects

💾 SQLite Integration
All predictions are stored in a database:

File: database.db

Table: predictions

Fields:

input: raw input data (flattened image)

predicted: predicted digit label

👤 Author
Sabina S.
Aspiring ML Engineer / Data Scientist

🤝 Why I Built This
This project was requested as part of a hiring process to demonstrate:

My practical grasp of ML fundamentals

My ability to build working models without black-box libraries

Clean, professional, and documented code practices

📬 Let's Connect
Feel free to reach out via GitHub or LinkedIn if you'd like to discuss this project or explore how I can contribute to your team.
