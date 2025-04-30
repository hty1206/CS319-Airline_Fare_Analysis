# ␟✈️ CS319-Airline_Fare_Analysis
## ☞ Introduction  
This is an end of term project of CS319 at the University of Wisconsin - Madison. I chose this project because I love traveling, but I've noticed that flight ticket prices can fluctuate quite a bit. This sparked my interest in understanding these fluctuations, and I want to dig deeper into analyzing fare trends and identifying the factors that influence ticket prices.

## ☞ Objectives
- **Airline Fare Adjustments:** Examining how airlines like UA and AA (high-priced) and G4, F9 (low-priced) adjust fares based on demand and the pandemic.  
- **Fare Trends:** Analyzing fare reductions in 2020-2021, post-pandemic changes, and seasonal fare variations to predict future trends.  
- **Factors Affecting Fares:** Identifying the impact of seasons, market demand, and unexpected events like the pandemic on prices.  
- **Consumer Insights:** Helping regular flyers identify the best times to buy tickets and select airlines effectively.

## ☞ Project Process  
1. Project Planning and Objective Definition
2. Fetching the Data
3. Data Collection and Preprocessing
4. Exploratory Data Analysis (EDA)
5. Data Visualization [document here](CS319_code_Hu.ipynb)
6. Summary

## ☞ Data Overview  
| Column Name         | Description                                                |
|---------------------|------------------------------------------------------------|
| `Year`              | Year                                                       |
| `quarter`           | Quarter                                                    |
| `mkt_fare`          | The average fare for the route for the airline             |
| `city1`             | The name and state of the first city                       |
| `city2`             | The name and state of the second city                      |
| `carairlineid`      | The airline ID identifying the airline operating the flight|
| `car`               | The airline code identifying the airline                   |
| `carpax`            | The number of passengers carried by the airline on the route|
| `carpaxshare`       | The market share of the airline on a specific route        |
| `caravgfare`        | Carrier’s average fare for the route                       |
| `fareinc_min`       | The smallest fare change                                   |
| `fareinc_minpaxsh`  | The share of passengers paying the minimum fare increase   |
| `fareinc_max`       | The largest fare change                                    |
| `fareinc_maxpaxsh`  | The share of passengers paying the maximum fare increase   |
| `fare_inc_x3paxsh`  | The percentage of passengers paying three times minimum fare |
| `price_category`    | **Derived Column**, Fare category (e.g., Low, Medium, High fare levels) |
| `demand_level`      | **Derived Column**, Demand level for the flight (e.g., High, Medium, Low demand) |

## ☞ Summary
| **Category**        | **Airlines**                           | **Key Observations**                                                                                                                                                                |
|---------------------|----------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **High-Priced Airlines** | UA, AA                                 | - Prices are raised when demand increases **(Q18)** <br> - The top ten most expensive tickets in 2024 were sold by high-priced airlines **(Q9)** <br> - More affected during the pandemic **(Q13)** <br> - Significant price variation for high-priced airlines' routes **(Q16 & Q17)** |
| **Low-Priced Airlines** | AS (mid-range), F9, G4                 | - Lower-priced tickets sell more **(Q19)** <br> - Most of the top ten cheapest tickets in 2024 were sold by low-priced airlines (G4), with a few exceptions from UA (non-interstate routes like FL-FL & TX-TX) **(Q11)** <br> - Less affected or nearly no impact during the pandemic **(Q13)** <br> - Price increases for low-priced airlines are more stable compared to high-priced airlines **(Q16 & Q17)** |
| **Fare Trends**       | Overall Fare Changes                    | - In 2020 and 2021, ticket prices averaged lower **(Q7)**, but the proportion of passengers paying three times the minimum fare increased **(Q21)**, possibly because passengers perceived even the higher three-times fares as cheaper compared to previous years and opted for upgrades, etc. <br> - In 2024, both the most expensive and cheapest routes were influenced by the pandemic **(Q10 & Q12)** <br> - First and second quarters had the highest fares, followed by the third quarter, with the fourth quarter being the cheapest, but the difference is minimal **(Q6 & Q7)** <br>- In 2024, it can be observed that, overall, ticket prices tend to increase as demand rises **(Q20)**|  

## ☞ For More Detailed Information  
For more detailed information on the project, please see the [document here](CS319_code_Hu.ipynb).
