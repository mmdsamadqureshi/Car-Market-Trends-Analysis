# 🚗 Car Market Trends Analysis

## 📌 Project Overview

This project performs an Exploratory Data Analysis (EDA) on used car data from CarDekho to identify market trends and understand the key factors influencing vehicle selling prices.

The analysis explores how variables such as present price, fuel type, transmission, seller type, vehicle age, and kilometers driven relate to the resale value of cars.

---

## 🎯 Objectives

The key objectives of this project are:

* Analyze the distribution of cars based on fuel type.
* Understand the distribution of car selling prices.
* Compare average selling prices across different fuel types.
* Analyze the impact of transmission type on selling price.
* Compare selling prices between dealer and individual sellers.
* Examine the relationship between present price and selling price.
* Analyze the impact of vehicle age on resale value.
* Explore the relationship between kilometers driven and selling price.
* Identify the most common cars in the dataset.
* Understand correlations between numerical variables.

---

## 📂 Dataset

The dataset contains information about used cars, including:

| Feature       | Description               |
| ------------- | ------------------------- |
| Car_Name      | Name of the car           |
| Year          | Manufacturing year        |
| Selling_Price | Selling price of the car  |
| Present_Price | Current market price      |
| Kms_Driven    | Total kilometers driven   |
| Fuel_Type     | Type of fuel used         |
| Seller_Type   | Dealer or Individual      |
| Transmission  | Manual or Automatic       |
| Owner         | Number of previous owners |

### Dataset Summary

* Original Records: **301**
* Columns: **9**
* Duplicate Records Identified: **2**
* Duplicates Removed Before Analysis

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 🔍 Analysis Performed

### 1. Data Cleaning

* Checked dataset structure and data types.
* Identified missing values.
* Checked for duplicate records.
* Removed duplicate rows before performing analysis.

### 2. Exploratory Data Analysis

The following analyses were performed:

* Fuel Type Distribution
* Selling Price Distribution
* Average Selling Price by Fuel Type
* Average Selling Price by Transmission
* Average Present Price by Transmission
* Average Selling Price by Seller Type
* Present Price vs Selling Price
* Manufacturing Year vs Selling Price
* Car Age vs Selling Price
* Kilometers Driven vs Selling Price
* Top 10 Most Common Cars
* Correlation Heatmap

### 3. Feature Engineering

A new feature, **Car_Age**, was created using:

```text
Car_Age = 2026 - Year
```

This feature was used to analyze the relationship between vehicle age and selling price.

---

## 📊 Key Insights

### 🚘 Fuel Type

The dataset is dominated by **Petrol vehicles**, followed by Diesel cars, while CNG vehicles represent only a small portion of the dataset.

### 💰 Selling Price Distribution

Most cars fall within the lower-to-mid price range. A small number of expensive vehicles create a **right-skewed distribution**.

### ⛽ Fuel Type vs Selling Price

Diesel cars have the highest average selling price in this dataset.

### ⚙️ Transmission

Automatic cars generally have significantly higher selling prices compared to manual cars.

Automatic cars also have a higher average present price, which contributes to their higher resale values.

### 🏢 Seller Type

Cars listed by dealers tend to have higher average selling prices compared to cars sold by individual sellers.

### 📈 Present Price vs Selling Price

Present Price has a strong positive correlation of approximately **0.876** with Selling Price.

This indicates that cars with higher current market prices generally have higher resale values.

### 📅 Vehicle Age

Older cars generally tend to have lower selling prices, demonstrating the impact of depreciation on resale value.

### 🛣️ Kilometers Driven

Cars with higher mileage generally tend to have lower resale values, although mileage alone is not as strong a predictor as Present Price.

---

## 📈 Key Visualizations

The project includes visualizations such as:

* Bar Charts
* Count Plots
* Histograms
* Scatter Plots
* Correlation Heatmap

These visualizations help identify patterns and relationships within the used car market.

---

## 📁 Project Structure

```text
car-market-trends-analysis/
│
├── data/
│   └── car_dekho_data.csv
│
├── notebooks/
│   └── Car_Market_Trends_Analysis_EDA.ipynb
│
├── README.md
│
└── requirements.txt
```

---

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/your-username/car-market-trends-analysis.git
```

### 2. Navigate to the project directory

```bash
cd car-market-trends-analysis
```

### 3. Install required libraries

```bash
pip install -r requirements.txt
```

### 4. Run the Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook and run the cells to reproduce the analysis.

---

## 📚 Skills Demonstrated

* Data Cleaning
* Data Exploration
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Data Visualization
* Correlation Analysis
* Business Insight Generation
* Python Programming

---

## 👨‍💻 Author

**Muhammad Samad Qureshi**

Aspiring Data Analyst focused on transforming raw data into meaningful insights and supporting data-driven decision-making.

### Connect with me

* LinkedIn: Add your LinkedIn profile
* GitHub: Add your GitHub profile
