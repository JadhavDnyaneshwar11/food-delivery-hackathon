# Food Delivery Hackathon Analysis

## Introduction
This project is my submission for the Food Delivery Hackathon.  
I analyzed three datasets (`orders.csv`, `users.json`, `restaurants.sql`) using Python and Pandas in Jupyter Notebook.

## Workflow
1. Load datasets into Pandas.
2. Merge datasets on `user_id` and `restaurant_id`.
3. Perform analysis queries.
4. Save final merged dataset as `final_food_delivery_dataset.csv`.

## MCQ Answers

- City with highest revenue from Gold members → **Chennai**  
- Cuisine with highest average order value → **Mexican**  
- Distinct users with > ₹1000 total orders → **> 2000**  
- Rating range with highest revenue → **4.6 – 5.0**  
- Gold members’ highest average order value city → **Chennai**  
- Cuisine with lowest restaurants but strong revenue → **Chinese**  
- % of orders by Gold members → **50%**  
- Restaurant with highest avg order value (<20 orders) → **Grand Restaurant South Indian**  
- Highest revenue combo → **Gold + Italian cuisine**  
- Quarter with highest revenue → **Q3 (Jul–Sep)**

## Numerical Answers
- **Q1: Total orders placed by Gold members** → 4987  
- **Q2: Total revenue from Hyderabad city** → 1,889,367  
- **Q3: Distinct users who placed at least one order** → 2883  
- **Q4: Average order value for Gold members** → 797.15  
- **Q5: Orders placed for restaurants with rating ≥ 4.5** → 3374  
- **Q6: Orders in top revenue city among Gold members only** → Chennai → 1337 orders  
- **Q7: Membership + Cuisine revenue (highest combo)** → Gold + Italian cuisine  
- **Q8: Quarterly revenue (highest quarter)** → Q3 (Jul–Sep)

## Fill in the Blanks
- The column used to join `orders.csv` and `users.json` is **user_id**  
- The dataset containing cuisine and rating information is stored in **SQL** format  
- The total number of rows in the final merged dataset is **10,000**  
- If a user has no matching record in `users.json`, the merged values will be **null**  
- The Pandas function used to combine datasets based on a key is **merge**  
- The column `membership` in the final dataset originates from the **users.json** file  
- The join key used to combine orders data with restaurant details is **restaurant_id**  
- The column that helps identify the type of food served by a restaurant is **cuisine**  
- If a user places multiple orders, their personal details appear **multiple** times in the final merged dataset  

## Conclusion
This hackathon helped me practice:
- Loading multiple file formats (CSV, JSON, SQL)
- Merging datasets in Pandas
- Performing groupby and aggregation queries
- Documenting results clearly in Jupyter Notebook
