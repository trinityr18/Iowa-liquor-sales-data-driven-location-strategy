# Iowa-liquor-sales-data-driven-location-strategy
Geospatial Analysis | Clustering | Location Optimization

# Overview
This project analyzes the Iowa Liquor Sales dataset (2012–2017) to identify the top 10 recommended locations for launching an online alcohol delivery service, either through existing stores or new delivery centers.
Analysis is based on wholesale transactions from the Iowa Alcoholic Beverages Division to retail outlets across the state
Dataset: Iowa Liquor Sales (https://www.kaggle.com/datasets/residentmario/iowa-liquor-sales)

# Business Question
“What are the top 10 recommended locations for online alcohol delivery — either from an existing store or a new delivery centre?”

# Approach

1.Data Cleaning:
-Removed extreme outliers (99th percentile)
-Excluded bulk shipments (> 60 bottles or > 54L)
-Kept realistic bottle sizes (≤ 1,750 ml) and prices

2.Feature Engineering
-Sales, volume, transactions, price metrics
-Geospatial coordinates for clustering
-Clustering (k=10)
-Identified demand hotspots across the state

3.Store Ranking
Ranked stores by sales, transactions, and demand density

# Key Insights
Demand is strongest in Des Moines, Iowa City, Cedar Rapids, and Bettendorf, where high sales and dense transaction activity make these markets the most attractive for online alcohol delivery.
Top-performing stores such as Hy-Vee (Des Moines) with $20.6M in sales, Central City 2 (Des Moines) with $19.1M, and Hy-Vee Wine & Spirits (Iowa City) with $13.3M clearly dominate their regions. Their scale and consistent customer traffic make them ideal bases for store-led delivery operations.
Statewide demand is driven by a core set of fast-moving categories—Vodka, Canadian Whisky, Imported Vodka, American Whiskey, and Tequila—which should anchor the online assortment.
The analysis also highlights opportunity beyond the major metros, with underserved high-demand areas near the Illinois border showing strong potential for a new delivery centre pending further market validation.
