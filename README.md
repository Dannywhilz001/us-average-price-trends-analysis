# From Raw Data to Meaningful Insights: U.S. Average Price Trends Analysis (2015–2026)

## 1. Project Background

Price movements affect household budgets, purchasing decisions, and business operating costs. However, a broad summary of price changes does not always reveal how individual products and categories behave.

This project investigates historical U.S. average price movements across 74 tracked items and 12 product categories between January 2015 and July 2026.

Rather than focusing solely on producing visualisations, the analysis follows a structured process of data preparation, exploratory analysis, period comparison, KPI development, and analytical storytelling.

The final output is a two-page interactive Microsoft Excel dashboard designed to communicate both high-level findings and more detailed product-level observations.

## 2. Analytical Problem

The central analytical question was:

**How have the prices of selected U.S. products changed over time, and what meaningful patterns can be identified across items and product categories?**

The analysis aimed to answer the following questions:

1. How have monthly prices changed between 2015 and 2026?
2. Which items recorded the largest year-over-year increases?
3. Which items experienced the largest decreases?
4. How did the analysed product categories behave?
5. How many comparable items recorded increases versus decreases?
6. What practical implications can be considered from the observed price movements?

## 3. Dataset Scope

| Attribute | Value |
|---|---|
| Geographic scope | United States |
| Analysis period | January 2015 – July 2026 |
| Monthly observations | 8,869 |
| Tracked items | 74 |
| Product categories | 12 |
| Comparable items for YoY analysis | 60 |
| Latest available month | July 2026 |

The cleaned monthly dataset contains:

- Date
- Year
- Month_Number
- Item
- Unit
- Category
- Price
- Series_ID

The dataset was organised into structured monthly and item-summary worksheets to support analysis and reporting.

## 4. Project Workflow

### Stage 1: Data Preparation

The first stage focused on preparing the data for analysis.

Activities included:

- Organising monthly price observations.
- Structuring the dataset into an Excel table.
- Preparing date-related fields.
- Organising product names and category information.
- Retaining measurement units alongside price observations.
- Preparing an item-level summary for subsequent comparisons.

The objective was to create a consistent structure that could support filtering, aggregation, and analysis.

### Stage 2: Exploratory Data Analysis

The next stage involved examining the historical data to understand the available observations and identify useful analytical directions.

The analysis explored:

- Monthly price movements.
- Differences between product categories.
- Individual item trends.
- Historical changes across selected periods.

Five categories were selected for the main monthly trend visualisation to keep the executive dashboard focused.

### Stage 3: Year-over-Year Comparison

To examine more recent changes, July 2025 prices were compared with July 2026 prices.

Only items with observations in both periods were included in the comparable-item analysis.

The percentage change calculation was:

Percentage Change = ((Current Price - Previous Price) / Previous Price) × 100

This ensured that the comparison was based on the same item across the two periods rather than comparing unrelated products.

### Stage 4: KPI Development

The KPI worksheet was developed to provide a concise summary of the results.

The main indicators included:

- Total items tracked.
- Items with latest-month prices.
- Average item-level year-over-year percentage change.
- Items recording price increases.
- Items recording price decreases.

### Stage 5: Visualisation and Dashboard Development

Microsoft Excel was used to build PivotTables, PivotCharts, and interactive dashboard elements.

The dashboard was divided into two pages.

[Executive Overview](https://ibb.co/ymgd7Z2p) 

Designed to provide a high-level view of the analysis through:

- KPI cards.
- Monthly price trends across five selected categories.
- Category-level price change analysis.
- Top 10 price increases.
- Overall price movement.
- Category, Item, and Year slicers.

[Insights & Analysis](https://ibb.co/4n9xtzkb)

Designed to provide a more detailed interpretation through:

- Top 10 price decreases.
- Selected-item monthly price trends.
- Key insights.
- Potential impacts.
- Recommendations.
- An overview summary.

## 5. Challenges and Analytical Decisions

This project involved several considerations that influenced the analysis and dashboard design.

### Challenge 1: Different Measurement Units

The dataset contains products measured in different units.

For example, a price per gallon cannot be directly interpreted in the same way as a price per dozen or per pound.

**Analytical decision:**

Measurement units were retained as part of the dataset structure. Direct comparisons of raw prices across products with different units were treated cautiously.

A simple average of raw prices across such products should not be interpreted as a meaningful overall consumer price index.

### Challenge 2: Incomplete Comparison Coverage

Although 74 items were tracked, only 60 had comparable observations for July 2025 and July 2026.

**Analytical decision:**

The year-over-year comparison was restricted to those 60 items with observations in both periods.

This avoided treating missing observations as price increases or decreases.

### Challenge 3: PivotChart Colour Consistency

When category filters changed the series displayed in a PivotChart, the colours assigned to the categories could change.

**Analytical decision:**

The category slicer connection to the fixed five-category trend chart was reconsidered so that the chart could retain its intended category selection and presentation.

### Challenge 4: Dashboard Readability

Displaying too many categories, labels, and data points in one chart can make an interactive dashboard difficult to interpret.

**Analytical decision:**

The dashboard was separated into an executive overview and a detailed insights page. This allowed the most important findings to remain visible while additional analysis was presented separately.

## 6. Key Findings

### Finding 1: Overall Price Movement

Of the 60 comparable items:

- 36 recorded year-over-year price increases.
- 24 recorded year-over-year price decreases.

This indicates that more comparable items increased in price than decreased during the selected comparison period.

### Finding 2: Energy Price Movement

Energy recorded a median year-over-year price increase of 23.3%.

All eight analysed energy items recorded increases.

This highlights energy as a category deserving closer attention in the observed comparison.

### Finding 3: Egg Price Movement

Egg prices recorded a 39.2% year-over-year decrease, the largest decline among the analysed items.

This demonstrates that price movements were not uniform across the dataset.

### Finding 4: Average Item-Level Percentage Change

The simple average of the item-level year-over-year percentage changes was 4.25%.

This figure is an unweighted average of the comparable item-level percentage changes. It is not the official U.S. inflation rate, nor a weighted consumer price index.

## 7. Interpretation, Potential Impact, and Recommendations

### Overall Price Movement

**Interpretation:** More comparable items recorded increases than decreases.

**Potential impact:** This pattern may indicate additional spending pressure across some of the analysed products.

**Recommendation:** Consumers and businesses can monitor product-level price changes and review purchasing budgets.

### Energy

**Interpretation:** All eight analysed energy items increased, and the category's median increase was 23.3%.

**Potential impact:** Energy price increases may contribute to higher household expenses and business operating costs.

**Recommendation:** Businesses can examine energy consumption and consider efficiency measures where practical.

### Eggs

**Interpretation:** Egg prices decreased by 39.2%.

**Potential impact:** This may provide some price relief for consumers and businesses purchasing eggs.

**Recommendation:** Continue monitoring prices before assuming that the decline will persist.

## 8. Tools and Skills

**Primary tool:** Microsoft Excel

Skills applied:

- Data cleaning and preparation.
- Structured data organisation.
- Exploratory data analysis.
- Percentage change calculations.
- Year-over-year comparisons.
- KPI development.
- PivotTables.
- PivotCharts.
- Interactive slicers.
- Dashboard design.
- Data interpretation.
- Analytical storytelling.

## 9. Project Limitations

The findings should be interpreted within the scope of the available data.

- The analysis covers 74 tracked items, not every consumer product in the United States.
- Only 60 items had comparable observations for July 2025 and July 2026.
- The 4.25% KPI is an unweighted average of item-level percentage changes, not an official inflation measure.
- Different product measurement units limit the interpretation of simple averages of raw prices across categories.
- The analysis identifies observed price movements but does not establish the causes of those movements.
- Potential impacts and recommendations are interpretations, not measured causal effects.

## 10. Conclusion

This analysis demonstrates how monthly price observations can be transformed into structured findings and interactive visualisations.

The project combines data preparation, exploratory analysis, year-over-year comparisons, KPI development, and dashboard design to examine how selected U.S. product prices changed between 2015 and 2026.

Beyond the technical work, the project reinforces the importance of analytical judgement: understanding what the data can show, recognising what it cannot establish, and communicating findings responsibly.

The overall objective was not simply to build an Excel dashboard, but to develop a clearer analytical narrative from raw data.

## 11. Repository Structure

```text
us-average-price-trends-analysis/
│
├── README.md
│
├── dashboard/
│   └── US_Price_Trends_Analysis_Dashboard_2015-2026.xlsx
│
├── screenshots/
│   ├── executive-overview.png
│   └── insights-and-analysis.png
│
├── documentation/
│   └── methodology.md
│
└── data/
    └── README.md
```

**Author:** Oladotun Olawale

**Project:** U.S. Average Price Trends Analysis (2015–2026)

**Tool:** Microsoft Excel

**Focus:** Data Analytics | Data Visualisation | Dashboard Development         [LinkedIn](https://www.linkedin.com/in/oladotun-olawale)
