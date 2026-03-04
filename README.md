# Restaurant Data Analysis (EDA)

## Project Objective

The goal of this project is to analyze customer spending and tipping behavior in a restaurant dataset.
Using Python and data visualization tools, we explore patterns related to customer visits, spending habits, and tipping behavior.

---

## Tools Used

* Python
* Pandas
* Matplotlib
* Seaborn

---

## Dataset

The dataset used is the **Tips dataset**, which contains information about restaurant bills and tips.

Main variables include:

* **total_bill** : total amount of the bill
* **tip** : tip given by the customer
* **sex** : gender of the customer
* **smoker** : whether the customer is a smoker or not
* **day** : day of the week
* **time** : lunch or dinner
* **size** : number of people at the table

An additional feature was created:

* **tip_percentage** : percentage of the tip relative to the bill.

---

## Key Analyses Performed

The project includes several exploratory analyses:

* Number of visits by day
* Average bill by day
* Total revenue by day
* Average bill by time of day (Lunch vs Dinner)
* Average bill by group size
* Average bill by gender
* Average tip percentage by smoking status
* Distribution of tip percentage
* Bill distribution by day
* Bill distribution for Lunch vs Dinner
* Correlation between numerical variables

---

## Key Insights

* **Saturday** generates the highest number of visits.
* **Sunday** shows the highest average bill.
* **Dinner** tends to generate higher bills than **Lunch**.
* Larger groups tend to increase the total bill.
* Tip percentages are generally between **10% and 20%**.
* Smoking status has little impact on tipping behavior.

---

## How to Run the Project

1. Clone the repository
2. Open the notebook in VSCode or Jupyter
3. Run all cells to reproduce the analysis

