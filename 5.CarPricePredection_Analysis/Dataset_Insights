# Dataset Description: 

The Car Price Dataset contains 10,000 records with 10 attributes detailing used cars and their resale prices. It includes brand, model, year (2000–2023), engine size (1.0L–5.0L), fuel type, transmission, mileage, doors, owner count, and price ($2,000–$18,301). Newer cars, luxury brands, and lower mileage vehicles generally have higher prices. Automatic, diesel, and hybrid cars also tend to be more valuable. The dataset is ideal for price prediction models and market analysis, revealing trends such as depreciation patterns and the rising popularity of hybrid and electric vehicles due to environmental concerns.

## Columns in dataset: 

* Brand (object): The car manufacturer (e.g., Kia, Chevrolet, Mercedes, Audi, etc.).
* Model (object): The specific model of the car.
* Year (int64): The manufacturing year of the car (range: 2000 to 2023).
* Engine_Size (float64): The size of the engine in liters (range: 1.0L to 5.0L).
* Fuel_Type (object): The type of fuel used (e.g., Diesel, Hybrid, Electric).
* Transmission (object): The type of transmission (e.g., Manual, Automatic, Semi-Automatic).
* Mileage (int64): The total distance the car has traveled, in kilometers (range: 25 to 299,947).
* Doors (int64): The number of doors (range: 2 to 5).
* Owner_Count (int64): The number of previous owners (range: 1 to 5).
* Price (int64): The selling price of the car in USD (range: $2,000 to $18,301)

# DataSet Observation:
## Insights from the Car Price Dataset Visualizations
1. Price Trends by Year
    * The Price vs. Year scatter plot and violin plot reveal that newer cars (post-2015) have significantly higher prices, while       older models tend to be cheaper.
    * The median price steadily increases for recent cars, reflecting their higher market value.
2. Mileage and Price Relationship
    * The Mileage vs. Price scatter plot highlights a clear trend:
    * Cars with higher mileage tend to have lower prices, reflecting wear and depreciation.
    * Lower-mileage cars retain their value better, especially newer models.
3. Engine Size Impact
    * The Engine Size vs. Price and Engine Size vs. Mileage scatter plots show that:
    * Cars with larger engines generally have higher prices, indicating more powerful and premium vehicles.
    * Larger engines tend to have lower mileage, suggesting they may be used less frequently or preserved for special purposes.
4. Doors and Pricing
    The Price Distribution by Number of Doors plot shows that:
    * 4-door cars dominate the market and have the widest price range, likely due to their popularity and versatility.
    * 2-door cars are generally priced lower, possibly because they are less practical for families.
    * 5-door cars exhibit moderate pricing, often associated with hatchbacks or compact SUVs.
5. Ownership Patterns
    The Owner Count vs. Price plot reveals that:
    * Cars with fewer previous owners generally have higher prices, as they are perceived to be better maintained.
    * Cars with 3 or more owners tend to have lower prices, likely due to increased wear and potential maintenance issues.
6. Fuel Type and Transmission Insights
    From the earlier plots (which included fuel and transmission types):
    * Hybrid and electric cars have higher prices, reflecting their growing demand and eco-friendliness.
    * Automatic cars generally have higher resale values compared to manual cars, indicating a consumer preference for                 convenience.
7. Yearly Car Trends
    The Year vs. Number of Doors and Year-wise Car Count plots show that:
    * The production of cars peaked between 2015 and 2020, indicating higher availability of newer cars in the dataset.
    * Most recent cars are 4-door models, reflecting their practicality and market preference.

## Linear Regression Model Insights:
### Feature Coefficients and Their Impact:

1. Year: +298.86

* For every one-year increase in the car's manufacturing year, the price increases by approximately $299.
* This reflects the higher value of newer cars.

2. Mileage: -0.0201

* For every additional mile driven, the price decreases by approximately $0.02.
* This shows that higher mileage reduces the car's value, as expected.

3. Engine Size: +1,002.57

* For every 1-liter increase in engine size, the price increases by approximately $1,003.
* Larger engines indicate more powerful and premium vehicles, resulting in higher prices.

4. Doors: -2.38

* Each additional door reduces the price by approximately $2.38, which is a negligible impact.
* This suggests that the number of doors has little influence on the car price in this dataset.

5. Owner Count: +6.41

* Each additional owner increases the price by approximately $6.41.
* This is likely due to insignificant correlation in the dataset between ownership history and price.
