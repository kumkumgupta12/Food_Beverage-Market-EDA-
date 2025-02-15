# Food_Beverage-Market-EDA-
Analysis on food and beverage market trends and finding out key insights. From data cleaning to data preprocessing, performing statistical tasks, EDA is done.

## Overview
This project is an exploratory data analysis (EDA) case study on food and beverage products. The analysis focuses on understanding product launches, unique flavors, market subcategories, and positioning strategies. The dataset is analyzed to gain insights into trends, unique flavor distributions, and consumer preferences. The project is particularly relevant for applications in companies of CPG market that deal with food industry analytics.

## Datasets Used
The following datasets were used for this analysis:
- **Product Launch Dataset.csv** - Contains details of food and beverage product launches.
- **Flavor Classification Dataset.csv** - Provides classifications of different flavors.
- **Positioning Category Mapping.csv** - Maps product positioning categories to product launches.

## Objectives
1. **Data Cleaning & Preparation:** Handling missing values and transforming data for better analysis.
2. **Unique Flavor Analysis:** Identify the number of unique flavors and analyze their trends.
3. **Market Subcategory Trends:** Explore product launches over time and identify declining categories.
4. **Flavor Group Analysis:** Analyze seasonal trends in product launches based on flavor types.
5. **Positioning Analysis:** Understand the distribution of product positioning groups.
6. **Time-based Launch Analysis:** Analyze trends in product launches over years, months, and quarters.
7. **Filtering and Subsetting:** Extract insights based on specific client requests.
8. **Hypothesis Testing:** Validate statistical significance in positioning categories.

## Data Preparation
- Missing values were handled: "Flavor" column had 1976 missing values, "Positioning" column had 4321 missing values.
- The "||" separator was used to split multiple variants and assign sub-product IDs (e.g., ID 7 with 5 variants was split into 7.1, 7.2, etc.).
- Merging and mapping datasets based on "Flavor" and "Positioning" attributes.

## Key Analyses and Insights
### 1. Unique Flavor Analysis
- **Result:** 10,881 unique flavors were identified.

### 2. Market Subcategory Trends
- **Findings:**
  - Decline observed in categories like Carbonates, Iced Tea, and Sports Drinks.
  - Bottled Water shows market saturation.
  - Niche categories like Sports Powders have very few launches.

### 3. Market Subcategory with Highest Unique Flavors
**Result:** **Juice & Juice Drinks** has the highest number of unique flavors (5,271).
- **Inference:** High consumer demand and intense competition drive product variety.

### 4. Seasonal Trends in Flavor Groups
- **Findings:**
  - Q2 (Spring) and Q3 (Summer) have the highest number of fruit-flavored product launches.
  - Q4 (Winter) has fewer fruit-flavored launches.

### 5. Positioning Analysis
- **Findings:**
  - **Convenience** (34% of launches) is the dominant positioning strategy.
  - **Ethical Positioning** accounts for 8% of launches, indicating a growing interest in sustainable products.

### 6. Time-based Launch Analysis
- **Findings:**
  - From 2008 to 2014, product launches increased, suggesting market growth.
  - Q2 and Q3 are peak launch periods, useful for strategic planning.

### 7. Filtered Data Based on Client Requests
**Case:** The client requested Canadian market data from 2013 for Energy Drinks with ethical packaging.
- **Result:** Only 4 products met the criteria, allowing for focused insights.

### 8. Top 5 Unique Flavors Across Countries (2013)
**Result:**
- Orange (Not Specified)
- Unflavored
- Apple (Red)
- Fruit (Not Specified)
- Lemon

### 9. Hypothesis Testing: Top 5 Positioning Groups
**Objective:** Statistically validate differences in positioning group counts.
- **Findings:**
  - **Top 5 Positioning Groups:** Convenience (12,986), Health (Passive) (9,858), Ethical (5,981), Choice (2,958), Health (Active) (2,648).
  - **Chi-Square Test:** P-value ~ 0, meaning the differences are statistically significant.
  - **Inference:** Convenience and Health (Passive) are major focus areas, while Ethical and Health (Active) are niche markets.

## Visualizations
-In "case study" doc file , all visualization with objective and inferences is mentioned.

**NOTE** - The doc does not require technical expertise rather focussed towards buisness perspective so stackholders and others can understand properly.
