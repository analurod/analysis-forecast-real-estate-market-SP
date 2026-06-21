# 🏠 Real Estate Price Analysis and Prediction in São Paulo

A Data Science project focused on São Paulo's real estate market, combining exploratory data analysis, statistical methods, and machine learning techniques to understand the factors associated with property sale and rental prices.

---

## 📌 Objective

The goal of this project is to investigate the main factors influencing property prices and develop a predictive model capable of estimating property values based on structural and location-related characteristics.

The main questions addressed were:

* Which features have the greatest impact on property prices?
* How does location affect sale and rental values?
* Is there a relationship between property size, infrastructure, and price?
* Can statistical and machine learning techniques accurately predict property values?

---

## 📊 Dataset

The dataset contains information about residential properties in São Paulo, including physical characteristics, location, and associated costs.

### Main Variables

| Variable  | Description              |
| --------- | ------------------------ |
| Price     | Property price           |
| District  | District/Neighborhood    |
| Size      | Property size (m²)       |
| Rooms     | Number of bedrooms       |
| Toilets   | Number of bathrooms      |
| Suites    | Number of suites         |
| Parking   | Number of parking spaces |
| Condo     | Condominium fee          |
| Elevator  | Elevator availability    |
| Furnished | Furnished property       |

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Statsmodels

---

## 🔎 Project Workflow

### 1. Data Preparation

* Data import and inspection
* Data cleaning and standardization
* Missing value treatment
* Categorical variable encoding

### 2. Exploratory Data Analysis (EDA)

Several analyses were performed to understand price distributions and identify relevant patterns.

Key analyses included:

* Distribution of rental and sale prices
* District-level price comparisons
* Relationship between property size and price
* Analysis of property characteristics
* Outlier identification

### 3. Statistical Analysis

Relationships between variables were investigated using statistical measures and correlation techniques.

Including:

* Correlation analysis among numerical variables
* Association analysis among categorical variables
* Interpretation of the most influential factors

### 4. Predictive Modeling

A multiple linear regression model was developed to estimate property sale prices.

Steps:

* Train-test split
* Model training
* Performance evaluation
* Comparison between actual and predicted values

---

## 📈 Key Insights

### 🏠 Rental and Sale Markets Behave Differently

Although both markets involve the same city and similar property characteristics, the ranking of the most valuable districts differs between rental and sale markets, suggesting that factors driving rental prices are not necessarily the same as those influencing sale prices.

### 📍 The Most Expensive Districts Are Concentrated in High-Income Areas

For rentals, districts such as Itaim Bibi, Iguatemi, and Alto de Pinheiros showed the highest average rental prices.

For sales, Iguatemi, Alto de Pinheiros, Itaim Bibi, Jardim Paulista, and Moema presented the highest average property values.

### 💰 Significant Price Inequality Exists Across Districts

The lowest average rental prices were observed in districts such as Itaim Paulista, Grajaú, and Lajeado.

For property sales, Cidade Tiradentes, Lajeado, Artur Alvim, Guaianases, and Perus showed the lowest average prices.

### 📊 Balanced Dataset Between Rental and Sale Properties

Rental properties account for approximately 53% of the dataset, while properties listed for sale represent around 47%, allowing meaningful comparisons between both markets.

### 📐 Property Size Has a Stronger Impact on Sale Prices

Larger properties tend to command higher sale prices. However, property size appears to have a less pronounced influence on rental prices.

### 🚗 Property Amenities Add Value

Features such as parking spaces, suites, and bathrooms are generally associated with higher property values.

### 🏢 Condominium Fees Are an Important Indicator

Higher condominium fees are commonly associated with premium properties. However, despite the strong correlation observed, correlation does not imply causation.

### 🤖 Statistical Modeling Enables Price Estimation

Multiple linear regression was able to capture the combined influence of property characteristics and provide reasonable estimates of property sale prices.

---

## 📊 Visualizations

### Price Distribution

#### Rental Properties

![Rental Price Distribution](img/image.png)

#### Properties for Sale

![Sale Price Distribution](img/image-1.png)

### Most Expensive and Cheapest Districts

#### Rental Market

![Most Expensive Rental Districts](img/image-2.png)

![Cheapest Rental Districts](img/image-3.png)

#### Sale Market

![Most Expensive Sale Districts](img/image-4.png)

![Cheapest Sale Districts](img/image-5.png)

### Property Size vs Price

#### Rental Market

![Rental Market Scatter Plot](img/image-6.png)

#### Sale Market

![Sale Market Scatter Plot](img/image-7.png)

### Correlation Matrix

#### Rental Market

![Rental Market Correlation Matrix](img/image-8.png)

#### Sale Market

![Sale Market Correlation Matrix](img/image-9.png)

### Actual vs Predicted Values

![Actual vs Predicted](img/image-10.png)

---

## 📂 Project Structure

```text
📁 real-estate-price-analysis-sp
│
├── img/
├── notebooks/
│   └── property_price_analysis.ipynb
│
└── README.md
```

---

## 📌 Conclusion

This project demonstrates how exploratory data analysis, statistical techniques, and machine learning can be applied to better understand the real estate market and identify the factors that influence property pricing.

The results highlight the importance of location, property characteristics, and market segmentation, while also showing that predictive models can provide valuable support for price estimation and decision-making processes in the real estate sector.

---

## 👩‍💻 Author

**Ana Luisa Rodrigues**

Computer Engineering Student | Python | Statistics | Machine Learning | Data Visualization
