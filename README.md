# Data Analysis Projects - Hong Kong Public Housing Analysis

**Introduction**

According to the Global Living 2020 report by CBRE research, Hong Kong property price once again became the most expensive place to purchase a property in the world. In general, the property market could be separated into two fields: the private housing side & the public housing side. For the private housing side, I already finished the personal project of Hong Kong private housing data analysis. Please also visit my GitHub repositories and Tableau for details.[1] For the public housing side, even Hong Kong is one of the most prosperous countries, part of citizens still cannot afford this sky-high property price. Therefore the public housing projects are still continuously planing and implementing since the British Hong Kong governance nowadays. It goals to provide a stable living environment for Hong Kong citizens. This project aims to provide a general view of Hong Kong public housing.



**Data Source**

Official Dataset of Location and Profile of Public Housing Estates by Hong Kong Housing Authority:
https://www.housingauthority.gov.hk/datagovhk/prh-estates.json




**Python Library use**

Numpy, Pandas, Requests, Matplotlib, Seaborn, Geopandas, Plotly, Descartes, Folium, 




**Workflow**
 
1. Quick review for the dataset
2. Data cleansing: Datatypes change, string handling, filling missing data
3. Data analysis & visualization: Findindg insights
4. Conclusion

[1] Github: https://github.com/paulcheng0830
    Tableau: https://public.tableau.com/profile/pc830
    



**Conclusion**

1. Geographically, the public housing estates are mostly built on New Territories West(Counts: 73), Kowloon East(Counts: 55) and New Territories East (Counts: 51) at the regional level. At the district level, Kwun Tong(Counts: 34), Kwai Tsing(Counts: 25) and Sha Tin(Counts: 22)are the top 3 of the largest number of public housing estates. 

2. 81% Estate type is public rental housing, which means most public housing could not sell and own by the Hong Kong government. However, some public housing could buy or rent under the tenants' purchase scheme (16.8%).

3. Most of the public housing was built in 1990 - 2010 due to the British colonial Hong Kong government response to the rapid economic growth.

4. If we focus on the intake year between 1980 -2000, it is easy to find that most of the small number of rental flats was built in this era.

5. Flats-Block Ratio is useful for finding which estate is more intensive: Hoi Tat Estate (Region: Kowloon West), Mei Tung Estate (Region: Kowloon East) and Tai Hing Estate(Region: New Territories West) is the top 3 intensive public estate. 

6. Not surprisingly, most of the property management company is Housing Authority Property due to the nature of public housing is mostly owned by Hong Kong government. However, the Carpark Management is mostly owned and operated by a private corporation.
