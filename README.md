# datafun-06-eda
Project: Begin with the end in mind

## Project Overview
This project performs comprehensive **Exploratory Data Analysis (EDA)** on the Seaborn **Diamonds dataset**. The dataset contains prices and attributes of over 50,000 diamonds, and the analysis explores how factors like **carat, cut, color, and clarity** affect price.  

The notebook includes descriptive statistics, data visualizations, and insights into diamond pricing patterns.  

---

# Diamonds EDA

## 📊 Dataset Information
**Source:** `seaborn.load_dataset('diamonds')`  

**Features:**

- **price**: Price in US dollars ($326–$18,823)  
- **carat**: Weight of the diamond (0.2–5.01)  
- **cut**: Quality of the cut (Fair, Good, Very Good, Premium, Ideal)  
- **color**: Diamond color, from J (worst) to D (best)  
- **clarity**: Measurement of how clear the diamond is (I1 [worst], SI2, …, IF [best])  
- **x, y, z**: Length, width, and depth in mm  
- **depth**: Total depth percentage  
- **table**: Width of the top of the diamond relative to widest point  

---

## 📁 Project Structure
```
diamonds-eda/
├── notebooks/
│   └── diamonds_eda.ipynb   # Main notebook with analysis
├── requirements.txt         # Python dependencies
└── README.md                # This file
```

---

## 🚀 Quick Start

Follow these steps to set up the project locally:

### 1️⃣ Clone the Repository
```
git clone https://github.com/bankoscarpa/datafun-06-eda
cd diamonds-eda
```

### 2️⃣ Create Virtual Environment & Activate
```
python -m venv .venv

# Windows
.venv\Scripts\activate

# Mac/Linux
source .venv/bin/activate
```

### 3️⃣ Install Dependencies
```
pip install -r requirements.txt
```

### 4️⃣ Launch Jupyter Notebook
```
jupyter notebook
```

Open `notebooks/diamonds_eda.ipynb` to start exploring the data and analysis.