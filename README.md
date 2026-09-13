# 📊 Self-Made Billionaires Data Analysis

[![Python](https://shields.io)](https://python.org)
[![Matplotlib](https://shields.io)](https://matplotlib.org)

An exploratory data analysis (EDA) and data visualization project focused on analyzing the demographic distribution and financial insights of **Self-Made Male vs. Female Billionaires** using Python.

---

## 📌 Project Overview
This project processes global wealth data to uncover the structural distribution of self-made billionaires. By analyzing patterns across genders, it provides statistical insights accompanied by highly customized graphical representations built with Matplotlib.

### 🗂️ Core Repository Files
* **`top-50-self-made-billionaires.ipynb`**: The primary Jupyter Notebook containing data cleaning, manipulation, and plotting scripts.
* **`Billionaires Statistics Dataset.csv`**: The raw statistical dataset used for performing data extraction.
* **`Self_base_Top_50.jpg`**: Visual chart export showcasing the targeted distribution findings.

---

## 🎨 Visualization Preview
Below is the data distribution preview generated directly from the analysis script:

![Top 50 Self-Made Billionaires](./Self_base_Top_50.jpg)

---

## 💻 Technical Setup & Installation

To run this repository locally on your computer, clone the repository and install the basic data science dependencies:

```bash
# Clone the repository
git clone https://github.com

# Navigate into the project folder
cd selfmade-billionaires-analysis

# Install standard required libraries
pip install matplotlib pandas numpy
```

---

## 🏗️ How the Script Works
1. **Data Aggregation:** The notebook reads the `Billionaires Statistics Dataset.csv` using Pandas.
2. **Filtering Engine:** Isolate profiles targeting specific categories focusing heavily on the `gender` distribution metrics.
3. **Data Visualization:** Employs Matplotlib to draw clean structural comparative bar charts utilizing modern aesthetic parameters.
