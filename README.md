# What Drives the Price of a Car?

Jupyter NoteBook link - 

### Problem statement:
Our goal is to understand the key factors that influence the price of used cars in your inventory. Using a dataset of vehicle listings, we have applied data cleaning, feature engineering, and statistical modeling to identify which attributes—such as age, mileage, condition, and brand—drive value.

### Findings:
**Evaluation of Results and Business Implications**

From a business perspective, these results showcase that the features listed below have the most impact on how much a buyer will spend on a used vehicle:

1. Vehicle Age and Mileage: Older vehicles and cars with higher odometer readings consistently sell for less. Buyers prioritize newer, low-mileage cars.
Brand and Manufacturer Reputation: Luxury and high-performance brands like Ferrari, Porsche, Tesla, and Aston Martin significantly increase perceived value, while lower-end brands tend to decrease it.
2. Vehicle Condition: Cars in excellent or like-new condition command higher prices, while fair, salvage, or rebuilt vehicles have diminished value.
3. Fuel Type and Engine Size: Diesel vehicles and cars with higher cylinder counts are valued more, whereas some electric and small-engine vehicles are less influential in price.
4. Vehicle Type: Convertibles, pickups, and SUVs generally have a higher market value than buses, hatchbacks, or wagons.
5. Title Status: Clean titles or lien-free vehicles increase buyer confidence and price potential; salvage or parts-only titles reduce it.
6. Regional Differences: Certain states (e.g., Utah, Montana, Washington) show higher valuation trends, suggesting regional demand patterns matter.

**Actionable Recommendations for the Dealership:**

1. Pricing Strategy: Use the Decision Tree and feature importance insights to develop a dynamic pricing model that considers age, mileage, brand, condition, and type. This ensures market-competitive, value-aligned pricing.
2.Inventory Management: Focus acquisition efforts on newer, low-mileage vehicles from high-demand brands. Refurbish vehicles with slightly lower condition scores to improve sale price. Consider geographic preferences when sourcing inventory.
3. Marketing and Sales: Highlight high-impact attributes — such as low mileage, clean title, fuel efficiency, or luxury brand — in online listings, showroom displays, and promotional materials. Tailor messaging based on vehicle type and regional demand trends.
4. Value-Adding Services: Offer minor maintenance, detailing, or feature upgrades to enhance perceived value. Even small improvements in condition or aesthetics can justify higher prices and attract more buyers.
5. Data-Driven Decision Making: Continuously track sales performance relative to feature importance to refine inventory acquisition, pricing, and marketing strategies over time. This allows the dealership to adapt to evolving consumer preferences.


### Data:
The data is in a structured, tabular format. The dataset contains 426,880 individual records (rows), each representing a used car listing. There are 18 attributes (columns) for each record.

#### Identities of the Fields
The dataset contains the following 18 fields and their respective data types:

. id (int64): A unique numerical identifier for each listing.
. region (object): The geographical region of the listing.
. price (int64): The listed price of the vehicle in USD.
year (float64): The model year of the vehicle.
manufacturer (object): The make or brand of the vehicle (e.g., Ford, Toyota).
model (object): The specific model of the vehicle (e.g., F-150, Camry).
condition (object): The described condition of the vehicle (e.g., good, excellent).
cylinders (object): The engine cylinder configuration.
fuel (object): The fuel type (e.g., gas, diesel).
odometer (float64): The mileage reading of the vehicle.
title_status (object): The status of the vehicle's title (e.g., clean, salvage).
transmission (object): The type of transmission (e.g., automatic, manual).
VIN (object): The vehicle identification number.
drive (object): The drivetrain (e.g., 4wd, fwd).
size (object): The size classification of the vehicle.
type (object): The body type of the vehicle (e.g., sedan, truck, SUV).
paint_color (object): The exterior color of the vehicle.
state (object): The U.S. state where the vehicle is listed.




