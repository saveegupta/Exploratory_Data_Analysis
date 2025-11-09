
# 🍽️ Zomato Data Analysis (EDA)

This project performs **Exploratory Data Analysis (EDA)** on the **Zomato restaurant dataset** to derive meaningful insights about restaurants, cuisines, ratings, costs, and customer preferences across different countries.
It focuses on **data cleaning**, **feature engineering**, and **visualization** to help understand Zomato’s business landscape and food trends globally.

---

## 📊 Project Overview

Zomato is one of the world’s largest restaurant aggregators and food delivery platforms.
This project aims to analyze its dataset to:

* Explore restaurant trends across different countries
* Identify top cuisines and high-rated restaurants
* Study customer rating distributions
* Analyze cost patterns for two people
* Perform feature engineering for better insights

---

## 🧩 Dataset Description

Three main files are used:

1. **`zomato.csv`** – Contains restaurant information (name, location, cuisines, price range, ratings, etc.)
2. **`Country-Code.xlsx`** – Provides country codes for mapping restaurant locations
3. **`1-eda-feature-engineering.ipynb`** – Jupyter Notebook containing the full analysis and visualizations

---

## 🧹 Data Preprocessing

Key steps included:

* Handling missing values and duplicates
* Merging datasets using `Country Code`
* Cleaning textual data (cuisines, city names, etc.)
* Encoding categorical variables
* Creating new features such as average cost per rating

---

## 📈 Exploratory Data Analysis

### 🔹 Univariate Analysis

* Distribution of aggregate ratings
* Popular cuisines and their frequencies
* Cost for two people across different ranges

### 🔹 Bivariate/Multivariate Analysis

* Relationship between rating and cost
* Country-wise analysis of restaurants
* Online delivery and table booking trends

### 🔹 Visualizations

* Bar plots, pie charts, and heatmaps using **Matplotlib** and **Seaborn**
* Insights presented using clear and intuitive graphs

---

## 🛠️ Technologies Used

* **Python** 🐍
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Jupyter Notebook** for analysis and visualization
* **Excel** for country code mapping

---

## 💡 Key Insights

* India has the highest number of listed restaurants.
* North Indian and Chinese cuisines are the most popular globally.
* Higher-rated restaurants generally charge more per meal.
* Online delivery is more prevalent in metropolitan areas.

---

## 🚀 How to Run the Project

1. Clone the repository

   ```bash
   git clone https://github.com/<your-username>/zomato-data-analysis.git
   ```
2. Navigate to the project directory

   ```bash
   cd zomato-data-analysis
   ```
3. Install dependencies

   ```bash
   pip install -r requirements.txt
   ```
4. Open the Jupyter Notebook

   ```bash
   jupyter notebook 1-eda-feature-engineering.ipynb
   ```

---

## 📚 Future Scope

* Build predictive models for restaurant ratings.
* Perform sentiment analysis using Zomato reviews.
* Create interactive dashboards using Plotly or Power BI.

---

## 👩‍💻 Author

**Savee Gupta**
Assistant Professor (AIML) | Data Science Enthusiast
📧 [saveegupta@email.com](mailto:saveegupta@email.com)
🔗 [LinkedIn](https://www.linkedin.com/in/savee-gupta/)

