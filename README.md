Python Matplotlib-Project

This program was written by Radha Mahalingam on 3-19-19

This project analyses the data provided by the ride sharing company to offer data-backed guidance on new opportunities 
for market differentiation. The data provided includes complete recordset of historic rides and about every active drivers, including details like city, driver count,individual fares, and city type.

Through this program, a bubble plot and couple of pie charts have been built.

The Bubble Plot showcases the the relationship between following four key variables:

    # Average Fare ($) Per City
    # Total Number of Rides Per City
    # Total Number of Drivers Per City
    # City Type (Urban, Suburban, Rural)

In addition,  three pie charts are created to implement the following objectives:

    # % of Total Fares by City Type
    # % of Total Rides by City Type
    # % of Total Drivers by City Type

This project uses OS, Pandas, numpy, Matplotlib libraries and the Jupyter Notebook

This project also makes sure the data is cleaned before being put to use to analyze and plot

Proper labeling of all the plots are done, including aspects like: Plot Titles, Axes Labels, Legend Labels, Wedge Percentages, 
and Wedge Labels. Proper care has been taken to make the plots to consider the following aesthetics at a minimum.

    # Pyber color scheme (Gold, SkyBlue, and Coral) are followed in producing your plot and pie charts.
    # When making the Bubble Plot, experimented with effects like `alpha`, `edgecolor`, and `linewidths`.
    # When making the Pie Charts, experimented with effects like `shadow`, `startangle`, and `explosion`.

Based on the data visualization, the following three key trends are clearly observed based on the plots and analysis.

Both the Bubble chart and Pie charts provide great insights on (1)Drivers utilization (2) Drivers Throughput/productivity and (3) Ride Profitability (Fare per ride) as it relates to the three city types - Urban, Suburban and Rural. These insights will help to focus on marketing the ride sharing services, incentivizing the driver partners and improving customer satisfaction.  One of the input that will be vital to further study / understand the trend will be the wait time for the service by the customers in those three city types.  Let us discuss the three observable trends and related insights:

1.  Drivers Utilization:  More drivers are in the Urban areas compared to Suburban and Rural areas.  Rural area represents really a smaller percentage of drivers (2.6%) compared to larger percentage (80.9%) in Urban areas followed by 15.5% in Suburban areas.  This may be due to the volume of demands for ride services in the three city types.  However, when you look at rides per driver, it shows there are more drivers in Urban areas compared to ride demands, with rural area project less drivers compared to ride demands in the rural areas. On average, drivers in urban area get 0.68 rides per driver (i.e. some drivers may not get a ride in a typical day), where as 1.6 rides per driver in rural areas with Suburban coming in between.  This shows that additional incentives and marketing need to be rolled out to attract ride passengers in Urban areas and attract the driver partners in Suburban and rural areas.

2.  Drivers Throughput / Productivity: Urban Driver partners on average get $16.6 fare per ride compared to $55.5 per ride for the Rural Driver partners, with Suburban driver coming in between ($39.5).  This shows the ride sharing faces intense competition for the market share in urban areas where as the competition is relatively modest in Rural and suburban areas. This also provides correlation to the fact that there are more drivers in the urban areas which increases the imbalance between supply and demand.

3. Profitability (Fare per ride) :  On average, rural area rides provide better fare per ride ratio compared to Urban areas.  Each ride in the rural area fetches $34.62 per ride compared to $24.53 per ride in Urban area, with Suburban coming in the middle ($30.87).  This could be due to the fact that the rides in urban areas are for short distances compared to Rural areas.  It could also be due to heavy competition, which lowers the ride price as part of variable pricing.

All the above three trends are appropriately visible in both bubble plot and pie charts.The bubble plot shows that there are more drivers from the urban areas concentracted on the rides which fetches low average fare per ride. On the other hand, there are 
very small percentage of drivers in the rural areas, concentrated on the rides which fetches higher average fare per ride, with Suburban coming just in the middle.



