**Airbnb Rental Investment Analysis**

An interactive Tableau dashboard exploring Airbnb listing data to help prospective property investors compare locations, understand pricing patterns, and evaluate bedroom-level competition in the United States.

Live dashboard: View the Tableau Public dashboard

**Project Overview**

Imagine having money to invest in a property in the United States and wanting to rent it out on Airbnb. The key questions are:
- Which ZIP codes have higher average Airbnb listing prices?
- Which areas could be worth investigating as potential investment locations?
- How do prices and demand patterns change throughout the year?
- How does the number of bedrooms relate to listing prices?
- How competitive is each bedroom category?
This project uses Airbnb listing data and Tableau visualisations to explore these questions. It is intended as an exploratory analysis tool to support further investment research—not as a guarantee of rental income or investment returns.

**Data Source**

- Dataset: Airbnb Listings 2016 Dataset – Kaggle
- Platform: Kaggle
- Analysis and visualisation: Tableau

Please refer to the Kaggle dataset page for the original data, its files, and any licensing or usage conditions.

**Data Preparation**

Before building the dashboard, I reviewed the available tables and their fields to understand how the data related to one another.

The preparation process included:

1. Inspecting the tables and identifying relevant fields.
2. Reviewing the relationships between tables.
3. Creating joins in Tableau where required to bring related information together.
4. Checking the relationship fields and join keys to ensure the tables connected using the appropriate columns.
5. Reviewing the resulting data before creating the visualisations.

Correct relationships and join keys are important because incorrect joins can lead to duplicated records or misleading aggregated values.

**Dashboard Walkthrough**

The dashboard contains five main visualisations.

**1. Average Airbnb Price by ZIP Code**

A bar chart comparing the average listing price across ZIP codes.

Business question: Which ZIP codes have the highest average Airbnb listing prices?

This view helps identify areas where hosts list properties at higher average prices. These locations may be worth investigating further, although a higher listing price does not automatically mean higher occupancy or profit.

**2. Average Price by Location (Map)**

A map displaying the geographic distribution of Airbnb listing prices by ZIP code.

Business question: Where are the listings located, and which areas should an investor explore?

The map provides geographic context alongside the average price and ZIP code, making it easier to compare locations and identify areas of interest.

**3. Seasonal Pricing and Availability Trends**

A time-based visualisation exploring how Airbnb activity and pricing patterns vary throughout the year.

Business question: When might be a suitable time of year to operate or promote an Airbnb property?

This view helps explore seasonal patterns, including periods around holidays and the winter travel season. Seasonal trends should be interpreted using the fields and time period available in the dataset; they do not independently prove future demand or revenue.

**4. Price by Number of Bedrooms**

A visualisation comparing listing prices across bedroom counts and property configurations.

Business question: How does the number of bedrooms relate to the price a host can charge?

This helps compare different property sizes and understand how bedroom count is associated with listing prices.

**5. Competition by Bedroom Count**

A visualisation comparing the number of Airbnb listings across bedroom categories.

Business question: How much competition exists for each type of property?

This view helps show which bedroom categories have more or fewer competing listings. It can be considered alongside the price analysis when evaluating a potential property type.

**Tools and Skills**

- Tableau: Data relationships, joins, calculated analysis, charts, maps, dashboard development, and interactive data visualisation.
- Data analysis: Data inspection, field selection, comparing averages, and identifying patterns.
- Business analysis: Translating an investment question into measurable questions and visual insights.

**Key Takeaways**

The dashboard brings together several perspectives that can be considered when researching an Airbnb investment:
- Location: Compare average listing prices across ZIP codes.
- Geography: Explore where higher-priced listings are concentrated.
- Seasonality: Investigate how activity or pricing varies over time.
- Property type: Compare prices across bedroom counts.
- Competition: Understand how many listings compete within each bedroom category.

A sound investment decision would require additional research, including occupancy rates, actual booked-night revenue, cleaning and management costs, taxes, insurance, maintenance, financing costs, local short-term-rental regulations, and seasonality across multiple years. Average listing prices alone are not enough to calculate rental income or return on investment.

**How to View the Project**
1. Open the published Tableau dashboard.
2. Explore the five visualisations.
3. Compare ZIP codes and locations using the average-price chart and map.
4. Review seasonal patterns, bedroom-level pricing, and listing competition.

**Author**
**Rajeshwaran Abiraj**
- Tableau Public: Airbnb Renting Analysis Dashboard
- GitHub: Abiraj21

This project was created for learning and portfolio purposes. The analysis is exploratory and should not be treated as financial, legal, or investment advice.
