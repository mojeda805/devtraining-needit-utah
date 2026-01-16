# 🍔 FoodHub Data Analysis

### 📄 Project Overview
This project analyzes order data from **FoodHub**, a food aggregator app (similar to UberEats or DoorDash), to derive actionable insights for improving customer experience and business revenue.

The analysis focuses on understanding customer demand, restaurant performance, and delivery efficiency across New York restaurants.

### 🎯 Objective
As a Data Scientist, the goal was to answer key business questions, including:
* What are the most popular cuisines and restaurants?
* How do order trends differ between Weekdays vs. Weekends?
* What factors influence food preparation and delivery time?
* What is the distribution of customer ratings?

### 🛠️ Tech Stack
* **Language:** Python 3.x
* **Libraries:**
    * `pandas` (Data Manipulation)
    * `numpy` (Numerical Computation)
    * `seaborn` & `matplotlib` (Data Visualization)

### 📊 Dataset Description
The dataset contains **1,898 orders** with the following attributes:
* `order_id`: Unique ID for each order.
* `customer_id`: Unique ID for the customer.
* `restaurant_name`: Name of the restaurant.
* `cuisine_type`: Type of cuisine (e.g., American, Japanese).
* `cost_of_the_order`: Cost of the order in dollars.
* `day_of_the_week`: Weekend or Weekday.
* `rating`: Customer rating (1-5).
* `food_preparation_time`: Time taken to prepare food (minutes).
* `delivery_time`: Time taken to deliver food (minutes).

### 💡 Key Findings
* **Top Cuisines:** American, Japanese, Italian, and Chinese cuisines account for the majority of orders.
* **Order Timing:** The demand significantly spikes on **Weekends** compared to Weekdays.
* **Preparation Time:** The average food preparation time is approximately **27 minutes**.
* **Ratings:** A significant portion of orders (approx 38%) were not rated by customers, highlighting a potential area for app engagement improvement.

### 🚀 How to Run
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YOUR_USERNAME/FoodHub-Data-Analysis.git](https://github.com/YOUR_USERNAME/FoodHub-Data-Analysis.git)
    ```
2.  **Install dependencies:**
    Ensure you have Jupyter Notebook or Google Colab running.
    ```bash
    pip install pandas seaborn matplotlib numpy
    ```
3.  **Run the Notebook:**
    Open `FDS_Project_LearnerNotebook_FullCode.ipynb` to view the analysis and visualizations.

---
*This project was completed as part of the Foundations of Data Science curriculum.*
