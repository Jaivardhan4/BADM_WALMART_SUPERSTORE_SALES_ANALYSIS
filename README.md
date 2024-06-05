# Walmart Sales Analysis

## Table of Content
  * [Synopsis](#synopsis)
  * [Directory Tree](#directory_tree)
  * [Color Reference](#color_reference)
  * [Features](#features)
  * [Run Locally](#run_locally)

## Synopsis

Analysis of Walmart data was conducted using Microsoft Power BI, a potent tool for visualizing data. Unlike tools like Matplotlib or Seaborn, Power BI allows for interactive exploration of dashboards, facilitating deeper insights.

The dataset includes order IDs, ship dates, customer details such as location and region, sales indices, quantities, discounts, and profits. Initial visualization involved creating card charts for sales and profits, followed by a Treemap illustrating Walmart's profit across item categories.

Yearly sales and profits were visualized using an Area chart, while a clustered bar chart depicted repeat customers by counting order IDs associated with customer names.

A decomposition tree provided an overview of sales categories, branching into customer demographics like region. Overall, the visualization showcased various aspects of the dataset.

Additionally, two slicers were implemented—one for categories and another for subcategories—allowing users to dynamically impact other charts. Power BI emerged as a robust and user-friendly tool for data visualization.

## Directory Tree <a name='directory_tree'></a>

```
├── LICENSE
├── README.md
├── Result.png
├── Walmart.csv
├── Walmart.pbix
```
 
## Color Reference <a name='color_reference'></a>

| Color                         | Hex                                                                  |
| ------------------------------| ---------------------------------------------------------------------|
| Background of the dashboard   | ![#eb895f](https://via.placeholder.com/15/eb895f/eb895f.png) #eb895f |
| Card Chart                    | ![#ffffff](https://via.placeholder.com/15/fffff/ffffff.png) #ffffff |
| Tree map, Clustered bar chart | ![#000000](https://via.placeholder.com/15/000000/000000.png) #000000 |
| Slicer                        | ![#a0d1ff](https://via.placeholder.com/15/a0d1ff/a0d1ff.png) #a0d1ff |

## Features

- Easy to use.
- Helps organize data.
- Customize your dashboard.
- Offers many built-in analytics.

## Run Locally <a name='run_locally'></a>

Clone the project

```bash
  https://github.com/Jaivardhan4/BADM_WALMART_SUPERSTORE_SALES_ANALYSIS.git
```

Install dependencies

```bash
  Install Power-BI application
```

Open the dashboard

```bash
  Just double click on the dashboard (walmart.pbix) file and open it in power-bi application.
```