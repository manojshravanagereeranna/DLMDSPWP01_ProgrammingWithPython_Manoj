# DLMDSPWP01 – Programming with Python  
## Ideal Function Selection and Test Data Mapping

This repository contains the implementation and documentation for the **DLMDSPWP01 – Programming with Python** assignment.  
The project focuses on selecting ideal functions using the least-squares method, mapping test data using a deviation threshold, storing results in a SQLite database, and visualizing outputs using Python libraries.

---

## 📌 Project Overview

The main objectives of this project are:

- Load and preprocess training, ideal, and test datasets
- Select four ideal functions using **least-squares deviation**
- Map test data points using the **√2 deviation rule**
- Store all data and results in a **SQLite database** using SQLAlchemy
- Visualize training data, ideal functions, and mapped test data
- Apply object-oriented design concepts and basic unit testing
- Maintain version control using Git

---

## 📂 Project Structure

DLMDSPWP01_Programming_with_Python/
│
├── Data/
│ ├── train.csv # Training dataset (x, y1–y4)
│ ├── ideal.csv # Ideal functions (x, y1–y50)
│ └── test.csv # Test dataset (x, y)
│
├── UC-13606-3.ipynb # Main Jupyter Notebook implementation
├── requirements.txt # Python dependencies
│
├── .git/ # Git version control metadata
└── .ipynb_checkpoints/ # Jupyter notebook checkpoints


---

## ⚙️ Requirements

The project uses the following Python libraries:

- pandas  
- numpy  
- sqlalchemy  
- bokeh  
- matplotlib  

Install all dependencies using:

```bash
pip install -r requirements.txt
