# Call-Center-Dataset-Analysis-and-Profiling
This project performs end-to-end analysis and profiling of a call center management system using multiple interrelated CSV datasets.

# 📊 Call Center Dataset Analysis and Profiling

This project performs comprehensive data profiling and analysis of a call center management system using multiple interrelated datasets. It provides insights through preprocessing, statistical summaries, visual distributions, and correlation heatmaps.

---

## 🛠️ Features

- ✅ **Data Loading**: Loads multiple datasets related to calls, users, roles, queues, and more.
- 🔄 **Preprocessing**: 
  - Removes duplicates
  - Fills missing values using forward/backward fill
  - Filters outliers based on z-score (3σ rule)
- 📊 **Descriptive Statistics**: Provides summary statistics for each dataset.
- 📈 **Visualizations**:
  - Histograms with KDE plots
  - Correlation heatmaps for numeric data
- 🔍 **Correlation Analysis**: Highlights relationships between variables to derive actionable insights.

---

## 📁 Datasets Used

- `calls.csv`
- `counters.csv`
- `call_statuses.csv`
- `languages.csv`
- `permissions.csv`
- `queues.csv`
- `role_has_permissions.csv`
- `roles.csv`
- `services.csv`
- `users.csv`

---

## 🧪 Libraries Used

- [pandas](https://pandas.pydata.org/)
- [numpy](https://numpy.org/)
- [matplotlib](https://matplotlib.org/)
- [seaborn](https://seaborn.pydata.org/)

---

## 🚀 Getting Started

1. Clone this repository or download the script.
2. Ensure all required CSV files are located in the specified path (e.g., `/content/` for Colab or Jupyter).
3. Install required libraries if not already installed:

```bash
pip install pandas numpy matplotlib seaborn

Project Structure

📦 call-center-analysis/
 ┣ 📜 analysis_script.py
 ┣ 📂 data/
 ┃ ┣ 📄 calls.csv
 ┃ ┣ 📄 users.csv
 ┃ ┗ 📄 ...
 ┗ 📜 README.md


Sample Outputs
Distribution plots per dataset

Correlation heatmaps to visualize relationships

Console output of descriptive statistics

Author
Aashish Chaudhary

License
This project is licensed under the HIT License. Feel free to use and modify.

Let me know if you'd like to include sample images (e.g., histograms or heatmaps) and ready to push to GitHub.
