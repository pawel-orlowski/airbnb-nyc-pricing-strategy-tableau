# Airbnb NYC Pricing Strategy Dashboard

## Project Overview

This project analyzes Airbnb listings in New York City to support new hosts in choosing a competitive pricing strategy. The analysis focuses on identifying how location, room type, minimum night policy, host-related attributes, and demand indicators are associated with rental prices.

The final output is an interactive Tableau dashboard designed to help users compare market segments, evaluate pricing levels, and identify attractive entry opportunities for new Airbnb hosts.

## Business Problem

New Airbnb hosts often face uncertainty when setting the initial price for their listings. Pricing too high may reduce demand, while pricing too low may limit revenue potential. The goal of this project is to answer the following business question:

> How should a new Airbnb host choose a location, room type, and starting price to remain competitive while building early demand and reputation?

## Objectives

- Explore Airbnb listing data and understand the key variables related to price.
- Clean and prepare the data for analysis and visualization.
- Analyze price patterns by neighborhood, room type, demand, and minimum night policy.
- Build an interactive Tableau dashboard for market exploration.
- Provide practical pricing recommendations for new Airbnb hosts.

## Tools & Technologies

- Tableau
- Python
- Pandas
- Exploratory Data Analysis
- Data Cleaning
- Data Visualization
- Business Analysis

## Dataset

The dataset contains Airbnb listing-level data for New York City. It includes information such as:

- listing ID and host ID,
- neighborhood group and neighborhood,
- latitude and longitude,
- room type,
- price,
- minimum nights,
- number of reviews,
- reviews per month,
- availability,
- host verification status,
- instant booking availability.

## Methodology

### 1. Data Exploration

The dataset was reviewed to understand its structure, available variables, and potential relationships between listing characteristics and price. Key variables considered in the analysis included location, room type, minimum nights, demand indicators, host verification, and instant booking status.

### 2. Data Cleaning and Preparation

The data preparation process included:

- checking missing values,
- validating data types,
- preparing price and demand-related variables,
- grouping listings by market segment,
- preparing data for Tableau visualization.

### 3. Exploratory Data Analysis

The analysis focused on identifying:

- typical price levels across neighborhoods,
- differences between room types,
- relationship between price and demand,
- effect of minimum nights on pricing and demand,
- competitive segments with a balanced price-demand profile.

### 4. Dashboard Development

An interactive Tableau dashboard was created to allow users to explore pricing strategy scenarios. The dashboard includes filters, map-based exploration, ranking views, scatter plot segmentation, and minimum-night analysis.

## Dashboard Structure

The Tableau dashboard consists of the following views:

### 1. Map: Price and Demand

The map shows the geographical concentration of Airbnb listings and allows users to compare market density across locations.

### 2. Typical Price by Neighborhood

This ranking view compares median prices across neighborhoods. It also shows the level of competition based on the number of listings. Selecting a neighborhood filters the rest of the dashboard.

### 3. Demand vs. Price

This scatter plot compares median price with average reviews per month, which is used as a demand proxy. The chart divides the market into four business segments:

- **Risk**: high price and low demand,
- **Budget**: low price and low demand,
- **Premium**: high price and high demand,
- **Opportunity**: low price and high demand.

### 4. Minimum Nights vs. Price

This line chart shows how the required minimum number of nights relates to typical price levels and market competition.

## Dashboard Filters

The dashboard allows filtering by:

- room type,
- neighborhood group,
- instant booking availability,
- host verification status,
- minimum number of nights.

These filters make it possible to compare different market segments and test pricing scenarios.

## Key Insights

- The Airbnb market has a visible range of prices that appears more acceptable to customers.
- A higher price does not automatically lead to proportionally higher demand.
- The most attractive neighborhoods tend to have the highest competition.
- A high minimum-night requirement may reduce access to demand.
- The most balanced segments combine moderate prices, stable demand, and controlled competition.

## Recommendations for New Hosts

### Location Strategy

New hosts should consider neighborhoods with balanced competition rather than entering the most expensive and saturated areas immediately.

### Starting Price Strategy

A new host should consider setting the initial price around **5–10% below the neighborhood median**. This can help attract the first guests and build early reviews.

### Reputation Building

New hosts should avoid positioning themselves directly in the premium segment before gaining reviews and trust signals.

### Operational Settings

Recommended operational settings include:

- setting the minimum stay to approximately **2–5 nights**,
- enabling instant booking,
- focusing on fast response time and service quality,
- gradually increasing the price after receiving positive reviews.

## Main Business Conclusion

For new Airbnb hosts, the most effective entry strategy is not to maximize price from day one. A better approach is to enter the market with a competitive starting price, flexible booking conditions, and a strong focus on building reputation.

## Project Files

```text
.
├── README.md
├── Projekt.twbx
├── presentation/
│   └── Projekt Paweł Orłowski.pptx
├── instructions/
│   └── Projekt końcowy - instrukcje.docx
├── screenshots/
│   └── dashboard_preview.png
└── src/
    └── airbnb_analysis.py
```

Suggested files to add before publishing the repository:

- `dashboard_preview.png` – screenshot of the main Tableau dashboard,
- `airbnb_analysis.py` or `analysis.ipynb` – Python analysis script or notebook,
- `requirements.txt` – Python dependencies if Python code is included,
- `.gitignore` – to exclude temporary files and local system files.

## How to Use the Dashboard

1. Select a room type.
2. Choose a neighborhood group or click a bar in the neighborhood ranking.
3. Adjust the minimum number of nights.
4. Compare price and demand on the scatter plot.
5. Use the insights to define a competitive starting price.

## Author

Paweł Orłowski

Aspiring Junior Data Analyst / Junior Data Engineer focused on data analysis, dashboarding, and business-oriented data storytelling.
