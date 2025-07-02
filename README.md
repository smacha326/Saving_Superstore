# Superstore Profit & Returns Analysis

This is a Tableau project where I analyzed sales and returns data from a simulated Superstore. The goal was to help the business improve profits, make smarter advertising decisions, and reduce losses from returned products.

---

## 🧾 Part 1: Profits & Losses

I started by looking at which parts of the business are making or losing the most money.

### What I found:
- The **top 2 profit centers** were certain combinations of sub-categories and regions.
- The **biggest losses** came from a few underperforming products and regions.
- I recommended the store **stop selling** a few products that consistently lost money.
- I chose **3 subcategories to keep** (high profits) and **3 to drop** (consistent losses).

I used heatmaps and bar charts in Tableau to support these findings.

---

##  Part 2: Advertising Strategy

Next, I figured out where and when it would make sense to advertise.

### What I did:
- Found the **3 best states and months** to advertise in (based on profit patterns).
- Created a chart showing average profit by month for each state.
- Suggested an ad budget using a simple rule: spend 1/5 of the profit in those months.

This helps the store spend smarter instead of guessing.

---

##  Part 3: Returned Items

Finally, I looked into returns — which products and customers return items the most, and how returns affect profit.

### Steps:
- Joined the returns table with the orders table (so I could see what was returned).
- Created a new column where `Yes = 1` (returned), and `null = 0` (not returned).
- Found the **products and customers** with the highest return rates.
- Made a chart showing **average profit vs. return rate** by dimension (like state or shipping mode).

This helped show which areas of the business might be risky to keep.

---

Interactive Dashboards

- 👉 [Dashboard 1: Profit vs Loss Analysis](https://public.tableau.com/app/profile/sairamya.macha/viz/Book1_17458562594310/Dashboard3?publish=yes)
- 👉 [Dashboard 2: Product Performance](https://public.tableau.com/app/profile/sairamya.macha/viz/Book1_17458562594310/Dashboard1?publish=yes)
- 👉 [Dashboard 3: State-Level Advertising](https://public.tableau.com/app/profile/sairamya.macha/viz/Book1_17458562594310/Dashboard2_1?publish=yes)
- 👉 [Dashboard 4: Return Rate vs Profit](https://public.tableau.com/app/profile/sairamya.macha/viz/Book2_17460462965160/Sheet3?publish=yes)


## Tools Used
- Tableau
- Excel / Google Sheets

---
