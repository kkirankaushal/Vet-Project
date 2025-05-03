# 🐾 Veterinary Market Insights Dashboard

This project presents an interactive Tableau dashboard analyzing the veterinary service potential, community behavior, and market opportunity in a defined geographic area using demographic, consumer, and pet ownership data.

---

## 📊 Dashboard Objectives

The dashboard addresses five key business questions:

1. **Overview of the Area**  
   Presents population, household size, and family structure with trends from 2010 to 2028.

2. **Expected Veterinary Support from the Community**  
   Uses pet ownership statistics to estimate the potential client base for veterinary services.

3. **Impact of Another Vet Entering the Area**  
   Projects population and household growth rates to assess service demand sustainability.

4. **Market Share and Spending Capacity**  
   Highlights average household spending in relevant categories to gauge the financial opportunity.

5. **Community Loyalty Levels**  
   Examines pet food purchasing behavior to indicate consistency in pet care and potential long-term client value.

---

## 🗂️ Data Sources

All data is extracted from a cleaned Excel file (`Vet proj.xlsx`) with the following key sheets:

- `Summary`: Population, households, families (2010–2028)
- `Trends 2023–2028 Annual Rate`: Annual growth comparisons (local, state, national)
- `Household type`, `Age profile`, `Income`: Demographic breakdown
- `Current Cat and dog info`, `Current HH with petfood`: Pet ownership and loyalty indicators
- `Avg Category Spend`, `Sub Category`: Consumer spending patterns

---

## 🛠️ Tools Used

- **Tableau** – For data modeling and interactive dashboard creation
- **Microsoft Excel** – For initial data cleaning and structuring

---

## 📌 Key Features

- **Dynamic KPI Cards** showing real-time demographic metrics
- **Interactive Filters** by distance, year, or category
- **Donut and Bar Charts** for age and household type breakdown
- **Spending Heatmaps and Trend Visuals** to compare economic potential
- **Pet Ownership Visuals** highlighting market size and community loyalty

---

## 💡 Insights

- Identifies the **best radius for opening a new veterinary clinic**
- Reveals **potential underserved demographics**
- Helps stakeholders assess **customer loyalty and recurring revenue potential**

---

## 📁 File Structure

```bash
Vet-Market-Dashboard/
│
├── README.md
├── Vet proj.xlsx         # Cleaned source data
├── Veterinary_Dashboard.twbx  # Packaged Tableau dashboard file
└── Screenshots/          # Dashboard preview images
