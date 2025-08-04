# Hotel Booking Analysis

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on a **Hotel Booking Dataset** to identify important factors affecting hotel bookings. The dataset includes bookings for both **City Hotels** and **Resort Hotels**, with details such as:

- Booking time  
- Length of stay  
- Number of adults, children, and babies  
- Parking availability  
- Room types, meals, and customer types  

The analysis provides insights into **booking patterns, customer preferences, and revenue factors** to support **business decision-making**.

---

## 📊 Project Details

- **Project Type:** EDA (Exploratory Data Analysis)  
- **Contribution:** Individual  
- **Author:** Manisankar Dey  
- **GitHub Link:** [Hotel_Booking_Analysis](https://github.com/ManisankarDey/Hotel_Booking_Analysis)  

---

## 🎯 Problem Statement

We aim to **analyze hotel booking data** to understand:

- Customer preferences (hotel type, room type, meals, stay duration)  
- Booking trends (seasonal trends, repeated guests, cancellation rates)  
- Revenue-driving factors (ADR – Average Daily Rate)  

The **business objective** is to uncover insights that **increase hotel revenue, optimize operations, and improve customer satisfaction**.

---

## 🛠️ Technologies Used

- **Python 3**  
- **Pandas & NumPy** – Data Wrangling  
- **Matplotlib & Seaborn** – Data Visualization  
- **Google Colab** – Development Environment  

---

## 📂 Project Workflow

1. **Data Loading & Initial Exploration**  
   - Load the dataset from CSV  
   - Inspect rows, columns, and data types  

2. **Data Cleaning & Wrangling**  
   - Remove duplicates and handle missing values  
   - Create new columns: `total_stay` and `total_people`  
   - Remove invalid bookings (0 adults, children, and babies)  

3. **Exploratory Data Analysis (EDA)**  
   - **Univariate Analysis**: Hotel type, room type, meals  
   - **Bivariate Analysis**: ADR vs hotel type, cancellations per year  
   - **Multivariate Analysis**: Correlation heatmaps  

4. **Key Visualizations**  
   - Pie charts for preferred hotel type and repeated guests  
   - Bar plots for room type, meal type, and ADR comparison  
   - Line plot for seasonal booking trends  
   - Correlation heatmap for numerical features  

---

## 🔑 Key Insights

1. **City Hotels** are most preferred (~61%).  
2. **ADR (Average Daily Rate)** is higher for **City Hotels** than Resort Hotels.  
3. **Repeated Guests** are very low (~3.86%).  
4. **Room Type A** and **Meal BB** are most popular.  
5. **Peak bookings occur in July and August**, while Nov–Jan see low bookings.  
6. **2016 had the highest bookings**, and most cancellations occurred that year.  
7. **Portugal contributes the highest bookings** among countries.  
8. **Longer stays are rare**, and most stays are under 7 days.  
9. **More people per booking leads to higher ADR (revenue)**.  
10. **City Hotels have higher waiting lists**, indicating higher demand.

---

## 💡 Business Recommendations

- Promote **Resort Hotels** with targeted offers to balance demand.  
- Focus on **increasing repeated guest bookings** via loyalty programs.  
- Prepare for **peak seasons (July-August)** with sufficient staffing and inventory.  
- Investigate **high cancellation rates in 2016** and reduce cancellation risks.  
- Provide **special packages for 2–3 day stays**, as it’s the optimal duration.  

---

## 📈 Sample Visualizations

Some example visualizations included in the analysis:

- Pie chart: Most preferred hotel type  
- Bar chart: Average ADR per hotel type  
- Line plot: Monthly booking trends  
- Heatmap: Correlation among key features  

---

## ✅ Conclusion

The EDA provides **actionable insights** for hotel management to:

- Optimize room allocation and pricing  
- Increase revenue by targeting peak booking factors  
- Enhance guest experience and encourage repeat bookings  

---

### 🚀 Next Steps

- Implement **predictive modeling** for booking cancellations.  
- Create **interactive dashboards** using Power BI or Tableau.  
- Deploy findings into a **hotel revenue optimization system**.
