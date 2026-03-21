# Diwali Sales Data Analysis

## 📌 Project Overview

This project performs**Data cleaning and** **Exploratory Data Analysis (EDA)** on the Diwali Sales dataset to understand customer purchasing behavior during the Diwali festival. The analysis aims to identify patterns in customer characteristics and purchasing trends to derive useful business insights.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Dataset Description

The dataset contains information about customers and their purchases during the Diwali festival.

### Dataset Columns

* **User_ID** – Unique identifier for each customer
* **Cust_name** – Name of the customer
* **Product_ID** – ID of the purchased product
* **Gender** – Gender of the customer
* **Age Group** – Age category of the customer
* **Age** – Age of the customer
* **Marital_Status** – Marital status of the customer
* **State** – State of the customer
* **Zone** – Region of the customer
* **Occupation** – Occupation of the customer
* **Product_Category** – Category of the purchased product
* **Orders** – Number of orders placed
* **Amount** – Total purchase amount

---

## Data Cleaning

The following preprocessing steps were performed:

* Removed unnecessary columns (`Status`, `unnamed1`)
* Handled missing values
* Converted data types
* Cleaned column names

Example:

```python
df.drop(['Status','unnamed1'], axis=1, inplace=True)
df.dropna(inplace=True)
df['Amount'] = df['Amount'].astype(int)
```

---

## 📊 Exploratory Data Analysis

### Gender Analysis

Female customers contribute more to the overall sales compared to male customers.

### Age Group Analysis

Customers aged **26–35 years** make the highest number of purchases.

### State Analysis

Top purchasing states include:

* Uttar Pradesh
* Maharashtra
* Karnataka

### Marital Status Analysis

Married women contribute the most to the total sales during the Diwali festival.

### Occupation Analysis

Customers working in **IT, Healthcare, and Aviation sectors** tend to spend more.

### Product Category Analysis

Most purchased product categories include:

* Food
* Clothing & Apparel
* Electronics

---

## Key Insights

* Female customers spend more compared to male customers.
* The **26–35 age group** contributes the highest sales.
* Married women form the most active buyer segment.
* Most orders come from **Uttar Pradesh, Maharashtra, and Karnataka**.

---

##Project Structure

diwali-sales-data-analysis
│
├── Diwali_Sales_Analysis.ipynb
├── Diwali_Sales_Data.csv
├── README.md


---

## Author

Hammad Hussain
B.Tech AIML – BIT Mesra

