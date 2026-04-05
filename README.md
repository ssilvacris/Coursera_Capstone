# Analysis of Coffee Shops in Montreal: Neighbourhood Segmentation and Clustering

## Overview

This project explores the spatial distribution of coffee shops in Montreal by applying clustering techniques to segment neighbourhoods based on venue characteristics. The goal is to identify patterns in urban structure and provide insights into how coffee shops are distributed across the city.

This work was selected by Medium and the Towards Data Science platform as a hands-on tutorial, and I was invited to publish it through their channel.

This repository contains the full implementation of the project originally published as a Medium article:
[https://medium.com/data-science/analysis-of-coffee-shops-in-montreal-neighbourhood-segmentation-and-clustering-4e4f020c30d7](https://medium.com/data-science/analysis-of-coffee-shops-in-montreal-neighbourhood-segmentation-and-clustering-4e4f020c30d7)

## Objectives

* Segment Montreal neighbourhoods using venue data
* Identify clusters with similar characteristics
* Analyze the distribution of coffee shops across clusters
* Provide data-driven insights into urban patterns

## Methodology

The project follows a standard data science workflow:

1. **Data Collection**

   * Montreal neighbourhood data
   * Venue data retrieved via Foursquare API

2. **Data Preparation**

   * Cleaning and structuring neighbourhood and venue datasets
   * One-hot encoding of venue categories
   * Aggregation of features by neighbourhood

3. **Clustering**

   * Application of K-Means clustering
   * Selection of optimal number of clusters

4. **Analysis & Visualization**

   * Mapping clusters using Folium
   * Identification of dominant venue categories
   * Interpretation of coffee shop distribution patterns

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Folium
* Requests

## Key Results

* Neighbourhoods were grouped into distinct clusters based on venue composition
* Coffee shop presence varies significantly across clusters
* Central and dense areas show higher concentration of coffee shops
* Peripheral neighbourhoods present more homogeneous and less dense patterns

## Repository Structure

* `Capstone_Project.ipynb`: Main notebook with full analysis
* `data/` (if applicable): Input datasets
* `README.md`: Project documentation

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/ssilvacris/Coursera_Capstone.git
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

## Notes

This project was developed as part of the IBM Data Science Professional Certificate capstone. It focuses on applying clustering techniques to real-world location data.

## Author

Cristiane de Souza da Silva

## License

This project is for educational purposes.
