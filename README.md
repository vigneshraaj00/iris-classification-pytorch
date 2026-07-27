# 🌸 Iris Classification using PyTorch

A simple deep learning project that classifies Iris flowers into three species using a Feedforward Artificial Neural Network (ANN) built with **PyTorch**.

## 📌 Overview

This project demonstrates how to build, train, and evaluate a neural network for multiclass classification using the famous **Iris dataset**. It is a beginner-friendly implementation of supervised learning with PyTorch.

## 🚀 Features

* Built using **PyTorch**
* Feedforward Artificial Neural Network (ANN)
* Trained on the Iris dataset
* Predicts three Iris flower species
* Saves the trained model for future inference

## 🛠️ Technologies Used

* Python 3.x
* PyTorch
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Jupyter Notebook

## 📂 Project Structure

```
iris-classification-pytorch/
│── ex-2.ipynb           # Main notebook
│── my_iris_model.pt     # Saved trained model
│── README.md            # Project documentation
```

## 📊 Dataset

The project uses the **Iris Dataset**, which contains **150 samples** of iris flowers.

### Input Features

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

### Output Classes

* Iris Setosa
* Iris Versicolor
* Iris Virginica

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/iris-classification-pytorch.git
```

Move into the project directory:

```bash
cd iris-classification-pytorch
```

Install the required packages:

```bash
pip install torch torchvision torchaudio
pip install numpy pandas matplotlib scikit-learn jupyter
```

## ▶️ Running the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
ex-2.ipynb
```

Run all cells to train the neural network and generate predictions.

## 🧠 Model

The neural network consists of:

* Input Layer (4 Features)
* Hidden Layer(s)
* Output Layer (3 Classes)
* ReLU Activation
* Cross Entropy Loss
* Adam Optimizer

## 📈 Results

The model learns to classify Iris flower species with high accuracy after training. The trained model is saved as:

```
my_iris_model.pt
```

## 🎯 Future Improvements

* Hyperparameter tuning
* Add model evaluation metrics
* Confusion matrix visualization
* Deploy using Flask or Streamlit
* Create a web interface for predictions

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome. Feel free to fork the repository and submit a pull request.

## 📜 License

This project is intended for educational and learning purposes.

---

**Author:** Vignesh Raaj
