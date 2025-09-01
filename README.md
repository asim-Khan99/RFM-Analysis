
#  RFM Customer Segmentation Project

Welcome to my **RFM (Recency, Frequency, Monetary) Analysis** project! 🚀
This project applies customer segmentation techniques to group customers based on their purchasing behavior and assign them loyalty badges.

---

## ✨ Project Overview

Customer segmentation is a powerful tool in marketing and business strategy.
By analyzing **when customers purchased (Recency), how often they purchased (Frequency), and how much they spent (Monetary)**, businesses can design better:

* 🎯 Marketing campaigns
* 💡 Personalized offers
* 💎 Loyalty programs

In this project, I:

1. Prepared and cleaned transactional data.
2. Calculated **RFM metrics** for each customer.
3. Assigned **R, F, and M scores** using quantiles.
4. Computed a **Loyalty Score** and categorized customers into:

   * 🏆 Platinum
   * 🥇 Gold
   * 🥈 Silver
   * 🥉 Bronze

---

##  Tech Stack

* **Language:** Python 🐍
* **Libraries:**

  * `pandas` – Data wrangling
  * `numpy` – Numerical operations
  * `matplotlib` & `seaborn` – Visualizations

---

##  Steps in the Project

1. **Data Preparation**: Grouped customer transactions.
2. **RFM Calculation**: Extracted Recency, Frequency, and Monetary values.
3. **Scoring**: Applied quantile-based scoring functions.
4. **Segmentation**: Added Loyalty Score and Loyalty Badge.
5. **Final Output**: Exported customer segments for business use.

---

##  Sample Output

| CustomerID | Recency | Frequency | Monetary | LoyaltyBadge |
| ---------- | ------- | --------- | -------- | ------------ |
| 10001      | 12      | 8         | 1500     | Platinum     |
| 10002      | 65      | 3         | 400      | Bronze       |
| 10003      | 30      | 5         | 800      | Silver       |
| 10004      | 22      | 7         | 1200     | Gold         |

---

##  Visualizations (Optional Additions)

* Loyalty Badge distribution (Countplot)
* Recency vs Frequency (Scatter Plot)
* Customer ID vs Monetary (Bar chart)

---

##  Future Enhancements

* Integrate **K-Means clustering** with RFM features.
* Build **dashboards** in Power BI / Tableau.
* Automate pipeline for real-time segmentation.

---

## 🤝 Connect with Me

If you like this project, don’t forget to ⭐ star the repo!
Feel free to reach out for collaboration or feedback. 🙌
