Retail Price Elasticity & Demand Analysis

The Goal: 
I wanted to figure out exactly how price changes affect sales volume for different retail products. By calculating the Price Elasticity of Demand (PED), this project identifies which items should be put on sale to drive massive volume, and which items people will keep buying even if the price stays high.

Tools Used: Python (Pandas, NumPy, SciPy, Seaborn), Microsoft Excel

What I Did: 
1. **Data Prep:** I took raw transaction data from 2023–2024 and used Excel PivotTables to group hundreds of thousands of rows into clean, week-by-week summaries.
2. **Data Cleaning:** Handled missing product rows in Python using forward-fill, and converted the weekly sales and prices into log values to prep them for the model.
3. **Statistical Modeling:** Built a log-log linear regression model using SciPy. This let me calculate the exact elasticity score for each product, and I checked the P-values to make sure the trends were mathematically significant, not just random luck.
4. **Visualization:** Created a scatter plot with a regression line to clearly show the relationship between price drops and sales spikes.
