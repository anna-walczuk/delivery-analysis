# Delivery Performance Analysis (Python / Pandas)

This project explores delivery performance in an e-commerce dataset using Python and pandas.

The goal of the analysis is to understand delivery times and identify potential operational patterns such as delayed deliveries or unusually long delivery durations.

Dataset used:  
Brazilian E-Commerce Public Dataset (Olist)

https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

---

## Tools & Technologies

- Python
- pandas
- matplotlib
- Jupyter Notebook

---

## Analysis Steps

The project includes the following analysis steps:

1. Data loading and initial exploration
2. Data cleaning and date conversion
3. Delivery time calculation
4. Delivery time distribution analysis
5. Identification of extreme delivery times (outliers)
6. Analysis of delivery time vs number of items in an order

---

## Key Findings

- The average delivery time is around **12 days**.
- Most deliveries occur within **5–15 days**.
- A very small number of orders take significantly longer to deliver (over 60 days).
- The number of items in an order does **not significantly affect delivery time**.

---

## Project Structure

```
delivery-analysis/
│
├── notebooks/
│ └── delivery_analysis.ipynb
│
├── requirements.txt
└── README.md
```

---

## Next Steps

Possible extensions of this project:

- Analysis of late deliveries (actual vs estimated delivery date)
- Delivery performance by region
- Analysis of freight cost vs delivery time
