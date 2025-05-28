# Korea vs. U.S. Cost of Living Dashboard (2025)

This project compares the cost of living across six cities in South Korea and the United States using visualizations built in Tableau. It focuses on five key categories: rent, groceries, inexpensive meals, utilities, and public transit. Cities are grouped into three tiers to enable fair comparisons:

- **Tier 1 (Global Capitals):** Seoul vs. New York
- **Tier 2 (Large Metros):** Busan vs. Chicago
- **Tier 3 (Midsize Tech Hubs):** Daejeon vs. Austin

The goal was to explore urban affordability through data storytelling and build an interactive, transparent dashboard.

---

## 🔧 Tools Used

- **Google Sheets** – Data collection, conversion, and cleanup  
- **Tableau Public** – Visualization and dashboard building  
- **GitHub** – Documentation and version control  

---

## 🌐 Live Dashboard

📊 [Click here to view the final Tableau dashboard](https://public.tableau.com/app/profile/hyunjoon.mok/viz/SouthKoreavsUSACostofLiving/Dashboard)

---

## 📊 Key Features

- Tier-based city grouping for visual consistency
- Charts for 1BR rent, 3BR rent, grocery basket, restaurant meal, utilities, and transit cost
- Highlight table for side-by-side category comparison
- Tooltips and methodology notes embedded in the dashboard for transparency

---

## 🧠 Key Takeaways

- 1BR rent in New York is over **4× higher** than in Seoul; 3BR rent is nearly **9×** that of Busan
- Inexpensive restaurant meals are **2–4× more expensive** in U.S. cities than in Korean ones
- Grocery basket costs (milk, rice, eggs) are relatively similar across all cities
- Public transit in Daejeon costs only ~$10.98/month — less than 25% of what New Yorkers pay

---

## 📁 Data Sources & Assumptions

- **Primary Data Source:** [Numbeo.com](https://numbeo.com), collected May 2025
  - Numbeo’s built-in **currency conversion** to USD was used directly
- **Transit Cost (Daejeon):** Manually calculated based on ₩1,250/ride × 44 rides/month = ₩55,000 ≈ $10.98  
  - Source: [Daejeon Tourism Site](https://daejeontour.co.kr/en/page.do?menuIdx=358)
- **Utilities Breakdown:** 
  - Combined three values: electricity/water/heating ("basic utilities"), mobile plan, and broadband internet
- **Inexpensive Meal:** 
  - Defined as a basic restaurant meal for one adult at a casual eatery
  - Values vary widely; averages reflect crowdsourced estimates on Numbeo

---

## ⚠️ Data Limitations & Disclaimers

- **Crowdsourced Data:** Numbeo relies on user-submitted prices; city-level sample sizes vary
- **Estimates, Not Exact Values:** Prices are intended to reflect rough averages, not fixed standards
- **Exchange Rate Stability:** USD conversion depends on Numbeo’s rate at time of access (May 2025)
- **Variability Across Neighborhoods:** Rent and dining prices especially vary significantly within cities

These limitations are noted throughout the dashboard in the tooltips and summary notes.

---

## 📎 Files in This Repo

- `data/Korea_US_Cost_of_Living.csv` — Cleaned dataset used for Tableau
- `images/dashboard.png` — Screenshot of final dashboard
- `README.md` — Full project overview and source documentation

---

## ✍️ Author

**Hyunjoon Mok**  
[LinkedIn](www.linkedin.com/in/hyunjoon-mok-b29a9a252)  
[Tableau Public Profile](https://public.tableau.com/app/profile/hyunjoon.mok)

---

