# Airbnb NYC Exploratory Data Analysis

![New York City](/assets/nyc.png)
[![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)](https://plotly.com/)
[![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)](https://html.com/)
![CSS](https://img.shields.io/badge/css-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
[![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)](https://www.javascript.com/)

## About
Airbnb, Inc. is an American company that operates an online marketplace for lodging, with a primary focus on homestays for vacation rentals and tourism activities. Headquartered in San Francisco, California, the platform is accessible through both a website and a mobile app. Our project delves into the large dataset provided by the company to extract important references that significantly impact business metrics.

## Exploratory Data Analysis Process
In this project we use Python to explore data and statistical measures to communicate data concepts.

### Dataset
Get the dataset from Kaggle. There are total:
- 102599 listings
- 5 neighborhood groups: Manhattan, Brooklyn, Queens, Bronx, Staten Island.
- 4 room types: Private room, Entire home/Apartments, Shared room, Hotel room.

### Data Cleaning
Perform basic data cleaning, such as handling missing values and data type conversions.

### Choropleth Map
![word cloud](/assets/choropleth.png)
Visualize the distribution of Airbnb listings across a geographic area using a choropleth map.

### Scatter Plot
![word cloud](/assets/scatterplot.png)
Visualize the distribution of Airbnb price and rating in each neighborhood.

### Word Cloud
![word cloud](/assets/wordcloud.png)
Generate a word cloud from the names of listings.

### Stacked Bar Graph, Line Graph and Pie Chart
![word cloud](/assets/bargraph.png)
Create a bar graph to visualize the average price of room types (private room, entire home, shared room, hotel) in each neighborhood group.

### Results and Insights
This exploratory data analysis shows that there is not much of a correlation between price and customer satisfaction; it really depends on their budget and past experience. However, there are a lot of potential for private rooms and entire homes/apartments to be improved. Although Private rooms and Entire homes/Apartments dominate the number of listings on Airbnb (almost 98%), they generally have lower price and ratings compared to Shared rooms and Hotels. Given their prevalence, it can also be inferred that a significant portion of Airbnb's revenue is generated from commissions on these signature room types.

### Visualization and presentation
Please visit our [website](https://zoelesv.github.io/airbnbnyc/) for an interactive and responsive experience!
| ![Image 1](/assets/IMG_4072.png) | ![Image 2](/assets/IMG_4074.png) | ![Image 3](/assets/IMG_4082.png) | ![Image 4](/assets/IMG_4085.png) |
|:---------------------:|:---------------------:|:---------------------:|:---------------------:|

## Files and Directories
- assets - a directory contains all images and graph visualizations.
	- All Neighbourhoods blackbg.html
	- ...
- EDA_bar_graph.ipynb
- EDA_choropleth_Arios.ipynb
- EDA_scatter_plot.ipynb
- README.md
- index.html - main template for homepage when users go to the website.
- script.js
- style.css
- white.html - white template for homepage when users click the lightbulb.

## Installation
- Fork this repository.
- Update assets and EDA files.
- Update index.html and white.html with your own assets.

## Authors
- Visualization: Arios Tong, John Bailey, Zoe Le
- Website: Zoe Le [Git Repository](https://github.com/zoelesv/airbnbnyc)