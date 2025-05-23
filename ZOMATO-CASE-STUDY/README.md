# 📊 Zomato Profitability Case Study
## 🕵️‍♂️ Problem Statement
**The Mystery Man wants to uncover which restaurants are earning high profits but have kept it exclusive with no more than 5 orders. This case study uses SQL to solve the puzzle based on Zomato order and restaurant data.**

📁 Dataset Description

The case study uses two datasets:

1) zomato_order_details
  - OrderID
  - RestaurantID
  - OrderValue
  - Zomato_Discount
  - Merchant_Discount
  - Net_Value (Calculated)
  - Commision_Cutoff (Calculated)
2) zomato_restaurant_details
  - RestaurantID
  - RestaurantName
  - Commision %

## 🧠 Objective
Find restaurants that:

Have 5 or fewer orders, and
Generate high overall profit (net value).

## 🏆 Insights

- Reveals niche or premium restaurants that are highly profitable despite limited orders.
- Useful for identifying exclusive partnerships or potential premium listings.
