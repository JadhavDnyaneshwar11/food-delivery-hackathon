# Food Delivery Hackathon Analysis

## Introduction
This project is my submission for the Food Delivery Hackathon.  
I analyzed three datasets (`orders.csv`, `users.json`, `restaurants.sql`) using Python and Pandas in Jupyter Notebook.

## Workflow
1. Load datasets into Pandas.
2. Merge datasets on `user_id` and `restaurant_id`.
3. Perform analysis queries.
4. Save final merged dataset as `final_food_delivery_dataset.csv`.

## Results
- **Q1: Total orders placed by Gold members** → 4987  
- **Q2: Total revenue from Hyderabad city** → 1,889,367  
- **Q3: Distinct users who placed at least one order** → 2883  
- **Q4: Average order value for Gold members** → 797.15  
- **Q5: Orders placed for restaurants with rating ≥ 4.5** → 3374  
- **Q6: Orders in top revenue city among Gold members only** → Chennai → 1337 orders  
- **Q7: Membership + Cuisine revenue (highest combo)** → Gold + Italian cuisine  
- **Q8: Quarterly revenue (highest quarter)** → Q3 (Jul–Sep)

## MCQ Answers
1. City with highest revenue from Gold members → **Chennai**  
2. Cuisine with highest average order value → **Italian**  
3. Distinct users with > ₹1000 total orders → **1000 – 2000**  
4. Rating range with highest revenue → **4.6 – 5.0**  
5. Gold members’ highest average order value city → **Chennai**  
6. Cuisine with lowest restaurants but strong revenue → **Italian**  
7. % of orders by Gold members → **50%**  
8. Restaurant with highest avg order value (<20 orders) → **Grand Restaurant South Indian**  
9. Highest revenue combo → **Gold + Italian cuisine**  
10. Quarter with highest revenue → **Q3 (Jul–Sep)**

## Conclusion
This hackathon helped me practice:
- Loading multiple file formats (CSV, JSON, SQL)
- Merging datasets in Pandas
- Performing groupby and aggregation queries
- Documenting results clearly in Jupyter Notebook
