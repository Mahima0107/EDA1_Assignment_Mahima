# EDA1_Assignment_Mahima
This dataset provides detailed information on used cars, ideal for building predictive models, conducting exploratory data analysis (EDA), and understanding factors influencing car resale prices. It is commonly used in machine learning projects focused on price prediction and market analysis.
In this dataset we have to use 9 columns and 301 rows. and used pandas library for Data Cleaning: pandas provides tools to handle missing values, duplicates, and inconsistent data entries.
Data Transformation: With functions like groupby(), pivot_table(), and merge(), pandas facilitates complex data transformations.

📊 Features Description

Column Name     	      Description
Car_Name	          Name of the car model
Year	              Year of manufacture
Selling_Price      	Price at which the car is being sold (in lakhs)
Present_Price	      Ex-showroom price of the car when new (in lakhs)
Kms_Driven	        Total kilometers driven
Fuel_Type	          Type of fuel used (e.g., Petrol, Diesel, CNG)
Seller_Type	        Type of seller (e.g., Dealer, Individual)
Transmission	      Transmission type (e.g., Manual, Automatic)
Owner	              Number of previous owners (0, 1, 2, or 3+)

📈 Key Insights
Depreciation Trends: Cars depreciate significantly over time. Newer models tend to retain higher resale values, especially within the first 3–5 years.
Fuel Type Impact: Diesel vehicles often have higher resale values compared to petrol counterparts, likely due to better fuel efficiency and torque.
Transmission Preferences: Manual transmission cars dominate the dataset, but automatic cars, though fewer, often command higher resale prices.
Seller Type Influence: Cars sold by individual owners generally have lower asking prices than those sold by dealers, possibly due to added dealer margins.
Ownership Effect: Vehicles with fewer previous owners (especially first-hand) tend to have higher resale values, indicating buyer preference for less-used cars.
Mileage Considerations: Lower Kms_Driven correlates with higher selling prices, reflecting buyer preference for less-used vehicles.

🧠 Potential Use Cases
Price Prediction Models: Utilize regression algorithms to predict resale prices based on car features.
Market Analysis: Identify trends in car sales, popular models, and pricing strategies.
Customer Segmentation: Group customers based on preferences like fuel type, transmission, and budget.
Inventory Management: Assist dealerships in stocking cars that are in higher demand based on historical data.
