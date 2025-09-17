# CORD-19 Research Data Analysis and Streamlit App

This repository contains my assignment for analyzing the **CORD-19 research dataset** and building a simple **Streamlit application** for visualization.

## 📌 Project Overview

The goal of this project was to:

* Load and explore the `metadata.csv` file from the CORD-19 dataset.
* Clean and prepare the data (handle missing values, parse dates, etc.).
* Perform basic analysis:

  * Count publications by year
  * Identify top journals
  * Find frequent words in paper titles
* Create meaningful visualizations (bar charts, word cloud, etc.).
* Experiment with a simple **Streamlit app** for interactivity.

## ⚙️ Tools Used

* Python 3.9+
* pandas (data manipulation)
* matplotlib & seaborn (visualization)
* wordcloud (text analysis)
* Streamlit (interactive app, optional)

## 📊 Visualizations

* Publications over time
* Top publishing journals
* Word cloud of paper titles
* Distribution of papers by source

## 🚀 How to Run

This project was developed and run in **Google Colab**.

### Option 1: Run in Colab (Recommended)

1. Open the notebook directly in Colab:
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/vanessaNjoroge2/Python-Week-8-Assignment/blob/main/Week%208%20PythonAssignment.ipynb)

2. Run all the cells to reproduce the analysis and visualizations.

### Option 2: Run Locally (Optional)

If you prefer running locally:

1. Clone this repository:

   ```bash
   git clone https://github.com/vanessaNjoroge2/Python-Week-8-Assignment.git
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter notebook:

   ```bash
   jupyter notebook "Week 8 PythonAssignment.ipynb"
   ```
4. (Optional) To try the Streamlit app part:

   ```bash
   streamlit run app.py
   ```

## 📄 Dataset

* The dataset comes from the [CORD-19 Kaggle challenge](https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge).
* For this project, only the **metadata.csv** file was used.

## ✨ Learning Outcomes

Through this project, I practiced:

* Loading and cleaning real-world datasets.
* Performing exploratory data analysis (EDA).
* Creating visualizations to explore trends in COVID-19 research.
* Documenting and publishing work via GitHub.

---

👩‍💻 *Developed by Vanessa Wanjiru*
