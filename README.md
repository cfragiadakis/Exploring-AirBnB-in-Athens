# Exploring AirBnB in Athens
In this project, we conduct an exploratory data analysis (EDA) of AirBnB listings in Athens, leveraging data obtained from [Inside AirBnB](https://insideairbnb.com/get-the-data/). With the use of Python visualization libraries (`Matplotlib`, `Seaborn`, `Plotly`, `Folium`) we aim to extract insights about the effect of AirBnB in the city.


## Objectives
The primary objectives of the analysis include:

* Identifying the most popular neighborhoods in Athens and exploring their average listing prices.
* Analyze the availability of listings on a daily basis to identify booking trends.
* Calculating the average price per day for booking an AirBnB in Athens.
* Exploring the distribution of listings among hosts, to identify prominent hosts and discern whether listings are primarily owned by individuals or managed as part of business operations.

Furthermore, using the [data assumptions](https://insideairbnb.com/data-assumptions/) by Inside AirBnB, we can estimate:
* The Average Occupacy of a listing per month.
* The Average Monthly Income of a listing in Athens.

## Interactive Maps

We utilize the `folium` library to create two interactive maps of AirBnB listings in Athens:

1. The [first map](https://github.com/cfragiadakis/Exploring-AirBnB/blob/main/athens_airbnb_map.html) provides descriptive information for each listing, including neighbourhood, room type, and price.
2. The [second map](https://github.com/cfragiadakis/Exploring-AirBnB-in-Athens/blob/main/athens_airbnb_map2.html) visualizes listings based on their ratings and number of reviews, helping potential guests identify the best opportunities for booking in Athens.


---

The analysis can be replicated by using the data from any other city for which data is available on [Inside AirBnB](https://insideairbnb.com/get-the-data/). You can simply download and replace the data files within the notebook, and extract insights about AirBnB accross different landscapes.

--- 

1st Assignment for Applied Machine Learning 2024 (DMST, AUEB)

You can find the description of the assignment [here](https://github.com/cfragiadakis/Exploring-AirBnB-in-Athens/blob/main/assignment_description.ipynb).
