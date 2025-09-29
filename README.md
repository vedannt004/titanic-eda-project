# 🚢 Titanic Exploratory Data Analysis (EDA) Project

## Project Overview
This project fulfills a data science task focused on **Exploratory Data Analysis (EDA)** using the classic **Titanic** survival dataset. The primary objective was to extract meaningful insights, identify relationships, and uncover trends and anomalies using visual and statistical exploration techniques.

The analysis follows a structured process of data inspection, cleaning, transformation, and visualization, culminating in a summary of findings regarding the factors that influenced survival during the disaster.

## 🎯 Objective
* Extract actionable insights and patterns from the Titanic dataset.
* Gain proficiency in using Pandas, Matplotlib, and Seaborn for data manipulation and visualization.
* Identify key relationships between features (e.g., Pclass, Age, Fare) and the target variable (`Survived`).

## 🛠️ Tools and Libraries
| Tool | Purpose |
| :--- | :--- |
| **Python 3.x** | Core programming language. |
| **Jupyter Notebook** | Environment for interactive analysis (`Titanic_EDA.ipynb`). |
| **Pandas** | Data manipulation and cleaning. |
| **NumPy** | Numerical operations and array handling. |
| **Matplotlib** | Basic plotting library. |
| **Seaborn** | Advanced statistical data visualization. |

## 📊 Key Findings Summary (The "What")
The EDA revealed several strong indicators for survival. The most significant factors were aligned with the "women and children first" protocol:

1.  **Socio-Economic Status:** **Passenger Class (`Pclass`)** and **Fare** were the strongest predictors. First-class passengers had a disproportionately higher survival rate compared to third-class passengers.
2.  **Gender:** Females had a significantly higher survival rate than males (Standard finding for this dataset).
3.  **Age Distribution:** Children and very young passengers showed a better chance of survival, while the largest group of non-survivors was concentrated in the 20-30 age bracket.
4.  **Family Size:** Passengers traveling with a small to moderate number of family members (`SibSp` + `Parch`) had a slightly better survival probability than those traveling alone or in very large groups.

## 📂 Repository Contents
* `Titanic_EDA.ipynb`: The main Jupyter Notebook containing all the code, statistical outputs (`.describe()`, `.info()`, etc.), visualizations (histograms, boxplots, heatmaps), and detailed observations.
* `train.csv`: The raw Titanic training dataset used for the analysis (sourced from Kaggle).
* `README.md`: This project description and guide.

## 🚀 How to Run the Analysis (The "How")

### Prerequisites
1.  **Python** (3.7+)
2.  **VS Code** or any IDE that supports Jupyter Notebooks.

### Steps
1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/YourUsername/titanic-eda-project.git](https://github.com/YourUsername/titanic-eda-project.git)
    cd titanic-eda-project
    ```
2.  **Install Dependencies:**
    ```bash
    pip install pandas matplotlib seaborn numpy
    ```
3.  **Run the Notebook:**
    * Open `Titanic_EDA.ipynb` in VS Code or Jupyter.
    * Execute the cells sequentially to reproduce the data loading, cleaning, visualization, and output the final findings.
