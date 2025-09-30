# SVM on Nonlinear Data: Moons Dataset

## 🚀 Project Overview
This project demonstrates the use of **Support Vector Machines (SVM)** with both linear and RBF kernels on a nonlinear dataset generated using scikit-learn's `make_moons` function. The goal is to visualize and compare how different kernels handle nonlinear class boundaries, highlighting the power of kernel methods in SVMs.

## 📊 Motivation
- Real-world data is often **not linearly separable**.
- SVMs with kernel tricks (like RBF) can model complex, nonlinear boundaries.
- Visualizing these effects helps build intuition for kernel methods in machine learning.

## 🛠️ Features
- Generates a synthetic, nonlinear dataset (`make_moons`)
- Trains SVM classifiers with both linear and RBF kernels
- Visualizes decision boundaries, margins, and support vectors
- Compares the effectiveness of linear vs. nonlinear kernels

## 🧑‍💻 Tech Stack
- Python 3.x
- scikit-learn
- matplotlib
- numpy

## 📂 Project Structure
```
.
├── svm_moons.ipynb   # Main Colab notebook with code and visualizations
├── README.md         # Project documentation (this file)
```

## ⚡ Getting Started
### 1. Clone the repository
```bash
git clone https://github.com/AryanDayalani/svm-nonlinear-demo.git
cd svm-nonlinear-demo
```

### 2. Open in Google Colab
- Upload `svm_moons.ipynb` to [Google Colab](https://colab.research.google.com/)
- Or, open the notebook directly from GitHub in Colab

### 3. Install dependencies (if running locally)
```bash
pip install numpy matplotlib scikit-learn
```

## 📝 Usage
- Run the notebook cells step by step.
- Visualize how the SVM with a linear kernel fails to separate the moons, while the RBF kernel succeeds.
- Modify parameters (like `C`, `gamma`, or dataset noise) to experiment further.

## 📈 Results
- **Linear SVM:** Struggles with nonlinear data, resulting in poor separation.
- **RBF SVM:** Successfully finds a nonlinear boundary, accurately classifying the moons.

## 📚 References
- [scikit-learn SVM documentation](https://scikit-learn.org/stable/modules/svm.html)
- [scikit-learn make_moons documentation](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.make_moons.html)

## 🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

