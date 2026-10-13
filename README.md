# 📚 Data Science Internship Tasks

Six tasks from my data science internship, each in its own folder with the notebook and its data. Together they cover regression, clustering, classification, and exploratory data analysis in Python.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

## 🗂️ Tasks

| # | Folder | Task |
|---|--------|------|
| 1 | [01-study-hours-predictor](01-study-hours-predictor) | Linear regression that predicts a student's score from hours studied |
| 2 | [02-iris-kmeans](02-iris-kmeans) | K-means clustering of the Iris dataset, with the elbow method to pick the number of clusters |
| 3 | [03-superstore-eda](03-superstore-eda) | Exploratory analysis of Sample Superstore sales and profit by region, category, sub-category, and discount |
| 4 | [04-global-terrorism-eda](04-global-terrorism-eda) | Exploratory analysis of the Global Terrorism Database: attacks by year and by country |
| 5 | [05-ipl-eda](05-ipl-eda) | Exploratory analysis of Indian Premier League matches and deliveries |
| 6 | [06-iris-decision-tree](06-iris-decision-tree) | Decision tree classifier for Iris species, with the tree visualized |

## 📝 Data notes
- **Task 4:** the Global Terrorism Database CSV (`globalterrorismdb_0718dist.csv`, about 150 MB) is not included because of its size. Download it from [Kaggle](https://www.kaggle.com/datasets/START-UMD/gtd) and put it in `04-global-terrorism-eda/`.
- **Task 5:** unzip `Indian Premier League.zip` in `05-ipl-eda/` to get `matches.csv` and `deliveries.csv`.

## 🚀 Run locally

```bash
git clone https://github.com/ziauldin/data-science-internship-tasks.git
cd data-science-internship-tasks
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
jupyter notebook
```

## 🛠️ Tech stack
Python · Jupyter · pandas · NumPy · Matplotlib · Seaborn · scikit-learn
