# Crop Yield Insights
This project analyzes crop yield data from various farms, exploring factors like farm size, irrigation type, soil type, fertilizer and pesticide use, and seasonal variations. The objective is to identify patterns that impact crop yield efficiency.

## Key Insights
- The farmlands support a decent vaFarmlands support diverse crops with 100+ kg/acre yields.
- Rainfall remains the most effective irrigation method.
- Loamy soil boosts sugarcane yield, while peaty soil favors carrots.
- Zaid season supports a wider crop variety with strong yields.
- More fertilizer/pesticides don’t always mean better yields—soil testing and expert supervision are key.

## Recommendations
1. Optimize irrigation methods such as Drip and Sprinkler systems to improve efficiency.
2. Prioritize high-yield crops like Tomato and Carrot in favourable conditions.
3. Optimize fertilizer and pesticide application based on crop needs to reduce costs and environmental impact.
4. Promote soil testing to match crops with the most suitable soil types.
5. Analyze seasonal patterns further to adjust planting schedules for maximum yield.


## Techniques & Procedures

#### Data Import and Cleaning:
The dataset contains 10 features, including "Crop_Type", "Farm_Area", "Irrigation_Type", "Fertilizer_Used", and "Yield" among others, with 50 records. It was imported into Excel as a single table. Upon review, no missing data and no duplicate records were identified.

#### Pivot Tables and Calculated Fields:
Used pivot tables to analyze yield variations based on crop type, irrigation type, soil type, season, fertilizer and pesticide use.
Added the following Calculated Fields:

- Avg Yield (kg/acre)
  * =('Yield(tons)'/'Farm_Area(acres)')*1000
- Avg Water Usage (m³/acre)
  * =('Water_Usage(cubic meters)'/'Farm_Area(acres)')
- Avg Yield (g/m³)
  * ='Yield(tons)'/'Water_Usage(cubic meters)'*10⁶
  
#### Data Exploration and Visualization:
- Bar Chart: Illustrated the average crop yield (kg/acre) by crop type, enabling a comparative analysis of productivity across different crops.
- Column Chart: Represented the mean yield (g/m³) by irrigation method, providing insights into the efficiency of various irrigation techniques.
- Tables: Summarized the optimal soil types and growing seasons for different crops, aiding in data-driven agricultural planning.
- Scatter Plots: Mapped the relationship between fertilizer and pesticide application and yield, revealing patterns and potential correlations.
