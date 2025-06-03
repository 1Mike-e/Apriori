# Apriori Association Rule Mining

This project implements the **Apriori algorithm** to find associations between items in a transactional dataset (market basket data). It uses the `apyori` Python package and displays the resulting association rules with relevant metrics like **support**, **confidence**, and **lift**.

---

## 📁 Dataset

- **Filename**: `Market_Basket_Optimisation.csv`
- **Format**: CSV with no header.
- **Rows**: 7,501 transactions
- **Columns**: Up to 20 items per transaction (some entries may be empty)

---

## 📦 Dependencies

Install required package using pip:

```bash
pip install apyori
