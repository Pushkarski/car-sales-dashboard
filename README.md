# Used Car Sales Dashboard

## Project Description  
This interactive dashboard explores used car sales data from the US. Built with **Python**, **Plotly**, and **Streamlit**, the app allows users to investigate how various vehicle attributes affect **price** and **listing duration**.

---

## Project Goals  
- Identify key factors that influence vehicle price  
- Explore how vehicle condition, type, mileage, and fuel type affect market behavior  
- Provide actionable insights for buyers and sellers  

---

## Hypotheses Tested

The following hypotheses were tested using exploratory data analysis (EDA):

1. **Higher mileage** leads to lower vehicle prices.  
2. **Newer vehicles** (recent model years) are generally more expensive.  
3. **Better vehicle condition** is associated with both higher price and faster sales.  
4. **Vehicle type** (e.g., SUV, truck, sedan) affects pricing — SUVs and trucks tend to cost more.  
5. **Fuel type** influences both **price** and **listing duration** — electric and hybrid vehicles show distinct patterns.

Each hypothesis was evaluated and visualized in the [`EDA.ipynb`](notebooks/EDA.ipynb) notebook using boxplots, histograms, scatter plots, and density heatmaps.

---

## Tech Stack  
- **Python**: pandas, plotly, streamlit  
- **Jupyter Notebook** (EDA)  
- **Git / GitHub**: version control  
- **Streamlit Cloud**: app deployment  

---

## Key Insights  
- **Newer and better-condition vehicles** are priced significantly higher  
- **Mileage above 100,000 miles** reduces price by 25–40%  
- **SUVs and trucks** are priced $5,000–10,000 higher than sedans  
- **Electric and hybrid cars** stay longer on the market but retain value better  

---

## How to Use  
1. Open the live dashboard  
2. Use the filters in the sidebar to select vehicle condition and type  
3. Explore interactive graphs to gain insights on price and time on market  

[**Launch Streamlit App**](https://car-sales-dashboard-cakl.onrender.com)

Note: The dashboard highlights the most interactive and user-relevant insights from the full exploratory analysis. For a complete review of all tested hypotheses and visualizations, see the EDA.ipynb notebook in the notebooks/ folder.

---

## Repository Structure  
```
car-sales-dashboard/
├── app.py                  # Streamlit app script
├── vehicles_us.csv         # Dataset
├── requirements.txt        # Python dependencies
├── README.md               # Project overview
└── notebooks/
    └── EDA.ipynb           # Exploratory data analysis (EDA)
```

---

## Status  
- EDA complete  
- Dashboard built with Streamlit  
- Deployed on Render  