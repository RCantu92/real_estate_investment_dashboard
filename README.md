# Real Estate Investment Dashboard

The goal of this dashboard is to provide charts, maps, and interactive visualizations that help people explore the data and determine if they want to invest in rental properties, in this example we used the location of San Francisco.

## Getting Started

## Background

This project aims to accomplish the following tasks:

1. Complete a notebook of rental analysis

2. Create a dashboard of interactive visualizations to explore the market data

---

### Rental Analysis

The first step to building the dashboard was to work out all of the calculations and visualizations in an analysis notebook. Once the code was worked out here, it was copied over to a dashboard code and used with Panel to create the final layout.

#### Housing Units Per Year

In this section, what was calculated was the number of housing units per year and visualized the results as a bar chart using the Pandas plot function.

#### Average Gross Rent in San Francisco Per Year

In this section, the project visualized the average gross rent per year to better understand the trends for rental income over time. The project visualized the average (mean) gross rent per year and visualized it as a line chart.

#### Average Sales Price Per Year

In this section, the project determined average sales price per year to better understand the sales price of the rental property over time. For example, a person will want to know if they should expect an increase or decrease in the property value over time so they can determine how long to hold the rental property. The project visualized the average (mean) `sales_price_sqr_foot` as a bar chart.

#### Average Prices By Neighborhood

In this section, it compared the average prices by neighborhood.

#### Top 10 Most Expensive Neighborhoods

In this section, it figured out which neighborhoods are the most expensive.

#### Parallel Coordinates and Parallel Categories Analysis

In this section, it used plotly express to create parallel coordinates and parallel categories visualizations so that people could interactively filter and explore various factors related to the sales price of the neighborhoods. It created the visualizations using the DataFrame of Average values per neighborhood.

#### Neighborhood Map

In this final section, it read in neighborhood location data and built an interactive map with the average prices per neighborhood.

### Dashboard

Now that it worked out all of the code and analysis, it used the Panel library to build an interactive dashboard for all of the visualizations.

## Built With

* [Python](https://www.python.org/) - Programming language.
* [Pandas](https://pandas.pydata.org/) - Data analysis and manipulation tool.
* [Mapbox API](https://www.mapbox.com/) - API used to access map data.

## Authors

* **Roberto Cantu**  - [GitHub](https://github.com/RCantu92)