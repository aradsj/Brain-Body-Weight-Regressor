# 🧠 Brain-Body-Weight-Regressor

Regression analysis to predict animal body weight based on brain weight. This project uses the **K-Nearest Neighbors (KNN)** model and demonstrates the critical need for **feature scaling** in distance-based algorithms.

---

## ✨ ML Details

* **Simple Regression:** Predicts Body Weight based on Brain Weight.
* **Data Handling:** Reads and processes data from a structured text file (`animals_weight.txt`).
* **Feature Scaling:** Mandatory use of **StandardScaler** to correctly process the widely varying weights.
* **K-Sensitivity Analysis:** Compares prediction results using different neighbor values (K=1, 3, 5) to understand model robustness.

---

## 🛠️ Technologies Used

| Technology | Role |
| :--- | :--- |
| **Python** | Core language. |
| **Jupyter Notebook** | Environment for code and results. |
| **Pandas / NumPy** | Data reading and manipulation of the text file. |
| **Scikit-learn** | Implementation of **KNeighborsRegressor** and **StandardScaler**. |

---

## 🚀 Getting Started

### Prerequisites
* Python 3.x
* Pip

### Installation

pip install pandas numpy scikit-learn jupyter
Execution
Clone the repository:


git clone https://github.com/YOUR_USERNAME/Brain-Body-Weight-Regressor.git
cd Brain-Body-Weight-Regressor
Run the Notebook:


jupyter notebook animal_weight.ipynb
📂 File Structure
animal_weight.ipynb: Jupyter Notebook with the complete analysis and model comparisons.

animals_weight.txt: Raw dataset of animal brain and body weights.
