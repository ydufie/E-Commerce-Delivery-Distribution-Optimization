# Affinity Labs Optimized Distribution System
This is a documentation of the optimization of a delivery distribution system. It follows the process of importing necessary libraries , loading data , data cleaning and validation , the optimization algorithm, and visualizations of results.


##  Project Objective

To analyze and improve the current delivery operations of an e-commerce company distributing goods from Lome, Togo to multiple centres across Ghana. The goal is to identify inefficiencies, recommend solutions, and simulate an improved truck assignment system.



##  Contents
- `orders.csv`, `trucks.csv`, `destination_centres.csv`: Cleaned datasets
- `E-commerce_Order_Yaa_Final.ipynb`: Python notebook containing data cleaning, logic implementation, and result visualizations
- `transformed_data.csv`: Output file after optimization logic

---

##  Part 1: Data Analysis (Metabase)

Key insights from the analysis:

-  **Order Status**: High number of `PENDING` orders indicates inefficiency in the truck assignment process
-  **Truck Utilization**: Uneven usage of trucks; some are over capacity while others are underutilized
-  **Centre Bottlenecks**: Specific centres face higher order volumes and delays
-  **Order Trends**: Midweek spikes in order volume not matched with truck scheduling

---

##  Tools & Technologies

- **Python (Pandas, Seaborn, Matplotlib)**
- **SQL (via Metabase)**
- **Jupyter Notebook**
- **Data Cleaning & Visualization**
- **GitHub for version control**

---

## 📎 How to Use

1. Clone the repo
2. Run the notebook: `E-commerce_Order_Yaa_Final.ipynb`
3. Explore dashboard insights in the Metabase collection
4. Review the `pending_orders.csv` for the updated delivery plan

---

##  Author

**Yaa Dufie Asamoa**  
Data Analyst   



##  Note

This project was completed as part of a technical assessment for Affinity Labs. All insights and logic are based on the sample dataset provided.

