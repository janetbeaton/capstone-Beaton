Capstone Project Janet Beaton
Applied Python for Data Analysis
Capstone Project - 5/20/2026

Using the city of Denver data from Inside Airbnb, https://insideairbnb.com, this project will analyze which Airbnb listing features and neighborhood locations have the greatest influence on nightly rental prices in order to help potential real estate investors identify the most profitable types of properties and areas for Airbnb investment.

The dataset was cleaned by removing unnecessary columns, handling missing values, converting prices to numeric format, and standardizing superhost indicators. Listings with fewer than 10 occupied nights were excluded to better represent properties with meaningful rental activity for investment analysis.

My analysis found that higher nightly prices and stronger occupancy rates are the biggest drivers of Airbnb revenue for investors. For family-friendly rentals under $200 and $55,000 annually, while near-full occupancy could produce up to $75,000 per year. These results suggest investors should focus on strategic pricing and maintaining high occupancy to maximize profitability.

A key limitation of this analysis is that it uses historical Airbnb data, which may not reflect current market conditions or changes in demand over time. Occupancy and revenue are often estimated rather than directly observed, which can introduce some uncertainty. In addition, important factors like property condition, photos, and host quality are not fully captured in the dataset. Finally, the results show correlations rather than true cause-and-effect relationships between price, occupancy, and revenue.

Future work could improve this analysis by incorporating more recent and granular data, including seasonal trends and location-based market conditions. Adding external datasets such as local housing prices, tourism demand, and neighborhood amenities could also improve predictive accuracy. In addition, applying more advanced modeling techniques could help better estimate causal relationships between price, occupancy, and revenue rather than just correlations.