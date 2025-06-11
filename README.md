# Task 6: Sales Trend Analysis Using Aggregations

**Objective**: Analyze monthly revenue and order volume using MySQL.

## Dataset:
- Table: `online_sales`
- Columns: `order_id`, `order_date`, `amount`, `product_id`

## Queries Used:
1. Monthly revenue and volume:
```sql
SELECT YEAR(order_date), MONTH(order_date), SUM(amount), COUNT(DISTINCT order_id) ...
