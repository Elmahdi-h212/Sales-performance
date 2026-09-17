# DAX Measures

```DAX
Total Orders = COUNTROWS(Sales)

Total Sales = SUM(Sales[Chiffre_Affaires])

Average Order Value =
DIVIDE(
    [Total Sales],
    [Total Orders]
)

Total Quantity =
SUM(Sales[Quantite])

Total Customers =
DISTINCTCOUNT(Sales[Client])
```

## Purpose
- **Total Orders**: total number of orders.
- **Total Sales**: total revenue.
- **Average Order Value**: average revenue per order.
- **Total Quantity**: total quantity sold.
- **Total Customers**: number of distinct customers.

> The dashboard also uses standard Power BI visuals, slicers and a sales-by-year analysis.
