# 🛒 Market Basket Analysis Using Apriori Algorithm

## 📌 Overview
This project applies the **Apriori algorithm** to a Market Basket Optimization dataset to identify **frequent itemsets** and generate **association rules** that reveal customer purchasing behavior.

Apriori is a classical algorithm used in retail analytics for discovering product combinations and designing cross-selling strategies.

---

## 📂 Dataset
- Market_Basket_Optimisation.csv
- Each row represents a transaction
- Each column represents an item purchased

---

## ⚙️ Algorithm Used
### Apriori (Association Rule Mining)
- Generates frequent itemsets using support threshold
- Builds rules using confidence & lift
- Easy to interpret
- Widely used in retail analytics

---

## 🧪 Methodology
1. Load dataset
2. Convert to transaction format
3. One-hot encode transactions
4. Apply Apriori with `min_support = 0.03`
5. Generate rules using confidence & lift
6. Analyze strong product associations

---

## 🛠️ Technologies Used
- Python
- Pandas
- mlxtend
- Jupyter Notebook / Kaggle

---

📊 Results
---
Discovered frequent itemsets (1-item, 2-item, 3-item)

Generated strong association rules

Identified products often bought together

Useful for recommendation systems and bundling

---
📈 Example Insights
---
Certain food items are frequently purchased together

Strong lift values indicate meaningful associations

Helps in store layout and promotions

---
Conclusion
---
Apriori provides clear and interpretable insights into customer purchasing patterns and remains a strong baseline for market basket analysis.

