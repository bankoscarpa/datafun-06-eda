# datafun-06-eda
Project: Begin with the end in mind

## Project Overview
This project performs comprehensive **Exploratory Data Analysis (EDA)** on the Seaborn **Diamonds dataset**. The dataset contains prices and attributes of over 50,000 diamonds, and the analysis explores how factors like **carat, cut, color, and clarity** affect price.  

The notebook includes descriptive statistics, data visualizations, and insights into diamond pricing patterns.  

---

##  Dataset Information
**Source:** `seaborn.load_dataset('diamonds')`  

**Features:**
- **price**: Price in US dollars (\$326–\$18,823)  
- **carat**: Weight of the diamond (0.2–5.01)  
- **cut**: Quality of the cut (Fair, Good, Very Good, Premium, Ideal)  
- **color**: Diamond color, from J (worst) to D (best)  
- **clarity**: Measurement of how clear the diamond is (I1 [worst], SI2, …, IF [best])  
- **x, y, z**: Length, width, and depth in mm  
- **depth**: Total depth percentage  
- **table**: Width of the top of the diamond relative to widest point  

## 📁 Project Structure
```text
diamonds-eda/
├── notebooks/
│   └── diamonds_eda.ipynb   # Main notebook with analysis
├── requirements.txt
└── README.md

**## Quick Start
1 - Clone this repo

git clone <(https://github.com/bankoscarpa/datafun-06-eda)>
cd diamonds-eda


2 - Create virtual environment & activate it

python -m venv .venv
.venv\Scripts\activate   # Windows
source .venv/bin/activate # Mac/Linux


3 - Install dependencies

pip install -r requirements.txt


4 - Launch Jupyter Notebook

jupyter notebook


## Learning Outcomes

Hands-on EDA workflow in Python

Data visualization with matplotlib and seaborn

Identifying patterns, trends, and insights from real-world data