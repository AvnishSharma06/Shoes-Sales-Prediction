# Shoes-Sales-Prediction
# 📊 Sales Data Analysis & Channel Performance

## 🚀 Project Overview

This project focuses on analyzing sales data to evaluate the performance of different sales channels. The analysis is performed using Python in a Jupyter Notebook.
The objective is to identify high-performing channels and generate actionable insights for better decision-making.

---

## 📁 Project Type

* Exploratory Data Analysis (EDA)

---

## 🛠️ Tech Stack

* Python 🐍
* Jupyter Notebook 📓
* Pandas
* Matplotlib

---

## 📊 Key Features

* Data preprocessing and cleaning
* Grouping data using `groupby`
* Revenue aggregation per sales channel
* Data visualization using bar charts
* Insight extraction from data

---

## 📌 Code Snippet

```python
channel_sales = df.groupby('Sales_Channel')['Revenue_USD'].sum()

channel_sales.plot(kind='bar')
plt.title("Sales Channel Performance")
plt.xlabel("Channel")
plt.ylabel("Revenue")
plt.show()
```

---

## 📈 Insights

* Identified the highest revenue-generating sales channel
* Compared performance across different channels
* Provided data-driven business insights

---

## 📂 Output

* Bar chart representing sales channel performance
* Aggregated revenue values per channel

---

## 🎯 Future Improvements

* Apply machine learning models for prediction
* Perform deeper statistical analysis

---

## 💡 Learnings

* Data aggregation and transformation
* Visualization techniques
* Interpreting real-world data

---

## 👨‍💻 Author

Avnish Sharma
