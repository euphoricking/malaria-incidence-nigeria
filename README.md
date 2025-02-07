# Malaria Incidence in Nigeria: A Geospatial Analysis
Welcome to our project repository! This project focuses on analyzing and visualizing malaria incidence data in Nigeria using advanced geospatial techniques and interactive data visualization. We combine two key components in this repository:

1. Data Disaggregation Notebook: A Jupyter Notebook that processes national malaria data by disaggregating it to the state level using population, Land Use Land Cover (LULC), 
   and environmental data (temperature and rainfall). This notebook calculates weighted risk scores to allocate malaria cases across Nigeria's states.

2. Interactive Dashboard: A Dash-based web application that presents our findings via an interactive choropleth map, trend charts, bar charts, and key performance indicator   
   (KPI) cards. The dashboard dynamically fetches data from a PostgreSQL database and allows filtering by year, indicator, and state.




# Project Overview
Nigeria continues to face one of the highest malaria burdens globally, significantly impacting vulnerable populations such as children under five and pregnant women. Our project employs Geographic Information Systems (GIS) alongside interactive story mapping to understand the spatial and temporal distribution of malaria across Nigeria’s 36 states and the Federal Capital Territory.

By integrating diverse data sources—including population statistics, LULC classifications, and environmental data (temperature and rainfall)—we are able to:

1. Pinpoint high-risk regions,
2. Analyze seasonal trends from 2010 to 2020, and
3. Provide insights that can help shape targeted public health interventions.
   
The project builds on previous research and data resources, such as the Malaria Atlas Project and official environmental datasets, to offer a robust, data-driven perspective on malaria transmission.

# Technologies Used
Our project leverages a suite of modern tools and libraries:

1. Python: For data processing and analysis.
2. Jupyter Notebook: For developing and documenting our data disaggregation workflow.
3. Dash & Plotly: For building the interactive dashboard.
4. Dash Leaflet: To display geospatial data on a map.
5. SQLAlchemy: For managing PostgreSQL database connections.
6. Pandas, GeoPandas, and Rasterio: For data manipulation and geospatial analysis.
7. PostgreSQL: As the backend database.

# Usage
1. Data Disaggregation Notebook:
   Explore and execute the notebook to see how national malaria data is disaggregated by state. The notebook explains each step—from merging datasets to calculating 
   environmental risk scores—and produces outputs that can be used in the dashboard.

2. Interactive Dashboard:
   Use the dashboard to interactively explore the malaria data. Adjust the filters (year, indicator, state) to view dynamic updates on the choropleth map, trend lines, bar      charts, and KPIs.

# Contributions
We welcome contributions and suggestions! If you have ideas for improvement or new features, please open an issue or submit a pull request. Your feedback will help us enhance this project.

# License
This project is licensed under the MIT License. 
