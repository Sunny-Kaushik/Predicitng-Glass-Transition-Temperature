# Predicting Glass Transition Temperature using Machine Learning

## Overview
This repository contains the code and dataset for predicting the **Glass Transition Temperature (Tg)** of organic compounds using machine learning techniques. The study explores the limitations of traditional empirical models, such as the **Boyer-Beaman rule**, and introduces a data-driven approach utilizing molecular descriptors, including branching, to improve Tg prediction.

## Background

**Soft Matter Physics**  
Soft matter physics deals with materials that can easily deform under external forces, such as **polymers, colloids, gels, foams, and biological tissues**. The glass transition temperature (Tg) is a key property in understanding the thermal behavior of these materials.

**Glass Transition Temperature (Tg)**  
Tg is the temperature at which a material transitions from a rigid, glassy state to a more flexible, rubbery state. This transition is critical in determining the mechanical and thermal properties of polymers and other amorphous materials.

## Approach

- **Feature Selection:** The study considers molecular descriptors like **branching, molecular weight, and functional group ratios** to predict Tg.
- **Machine Learning Models:** The models tested include **Linear Regression, Random Forest, Gradient Boosting, XGBoost, and Symbolic Regression**.
- **Evaluation Metrics:** Performance is measured using **R² score** and **Mean Squared Error (MSE)**.

## Key Findings

- The traditional **Boyer-Beaman rule** estimates Tg based on **melting temperature (Tm)**, but Tm measurements can be inconsistent.
- **Branching** is a more robust predictor than Tm, as it is a structural property of molecules and is independent of experimental variations.


## Installation & Usage

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/Tg_Prediction.git
cd Tg_Prediction

### 2. Install dependencies
pip install -r requirements.txt

### 3. To Run the Code

#### **Option 1: Running in Jupyter Notebook**
- Load the dataset (`final_dataset.csv`) in the `data/` directory.  
- Open Jupyter Notebook and navigate to the `notebooks/` folder.  
- Open **`Glass_Transition.ipynb`** and run each section sequentially.  

---

#### **Option 2: Running in VS Code**
- Open VS Code and ensure Jupyter support is enabled.  
- Navigate to the `notebooks/` folder and open **`Glass_Transition.ipynb`**.  
- Run the notebook cell-by-cell using the interactive Python environment.  

---

#### **Option 3: Running in Google Colab**
- Open Google Colab at [colab.research.google.com](https://colab.research.google.com).  
- Upload **`Glass_Transition.ipynb`** to Colab.  
- Upload the dataset manually or mount Google Drive if storing the dataset there.  
- Execute each section sequentially in Colab.  

@article{your_paper,
  title={Data-Driven Prediction of Glass Transition Temperature Using Molecular Structural Features.},
  author={S. Kaushik et al.},
  journal={International Conference on Computational Sciences 2025},
  year={2025}
}


