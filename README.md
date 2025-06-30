# Assignment4

# 📱 Google Play Store Apps – Exploratory Data Analysis and Feature Engineering

This project presents an in-depth **Exploratory Data Analysis (EDA)** and **Feature Engineering** workflow on the Google Play Store dataset, focusing on understanding app characteristics, user engagement, and uncovering hidden patterns that influence app popularity.

---

## 🎯 Objectives

- Analyze data distributions of numeric and categorical features
- Detect and handle missing values
- Identify and visualize outliers
- Uncover relationships between variables
- Summarize key insights using clear and informative visualizations

---

## 🗂️ Dataset Overview

- **Source:** [Google Play Store Apps Dataset](https://www.kaggle.com/lava18/google-play-store-apps)
- **Records:** ~10,841 apps
- **Features:**
  - App name, Category, Rating, Reviews, Size, Installs, Type (Free/Paid), Price, Content Rating, Genres, Last Updated, Current Version, Android Version

---

## ✨ Key Analyses & Visualizations

✅ **Univariate Analysis of Numerical Features**
- Rating distributions show most apps rated between 4–4.5
- Installs are heavily right-skewed, with a few apps exceeding 1 billion downloads
- Most updates were clustered around 2017–2018

✅ **Univariate Analysis of Categorical Features**
- The majority of apps are free and targeted toward "Everyone"
- "Family" and "Game" are the most common categories

✅ **Category Distribution**
- Pie chart of app categories highlighting the dominance of Family and Game apps
- Bar charts of the top 10 categories by count

✅ **Bivariate Analysis**
- Pairplots of numeric variables to explore correlations and detect clusters or trends

✅ **Popularity Analysis**
- Horizontal bar charts of the most installed apps by category (Games, Communication, Productivity, Social)
- Most popular categories by total installations

✅ **Outlier Detection**
- Boxplots and distribution plots to flag outliers in numeric features

---

## 🔍 Sample Insights

- **Family** and **Game** apps are the most prevalent in the store.
- A small fraction of apps contribute to the majority of installations.
- Free apps vastly outnumber paid apps.
- Content ratings are dominated by "Everyone."

---

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas** for data manipulation
- **NumPy** for numerical operations
- **Seaborn** and **Matplotlib** for visualization

---

## 🚀 Getting Started

1. **Clone this repository**
   ```bash
   git clone https://github.com/your-username/google-playstore-eda.git
   cd google-playstore-eda
````

2. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

   *(If `requirements.txt` is not included, install manually: `pandas`, `numpy`, `matplotlib`, `seaborn`.)*

3. **Launch Jupyter Notebook**

   ```bash
   jupyter notebook
   ```

   Open the main notebook and execute cells sequentially.

---

## 📂 Folder Structure

```
.
├── data/
│   └── googleplaystore.csv
├── notebooks/
│   └── google_playstore_eda.ipynb
├── images/
│   └── (visualization screenshots)
├── README.md
└── requirements.txt
```

---

## 📄 License

This project is open-source under the MIT License.

---

## 🙏 Acknowledgements

* **Kaggle** for providing the dataset.
* **Junaid Data** for EDA inspiration.
* Community contributors and open-source libraries.

---

## ✉️ Contact

**Your Name**
[GitHub](https://github.com/mdaftab20089) • [Email](mailto:aftabrahi20089@gmail.com)

``
