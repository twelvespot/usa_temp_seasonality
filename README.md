# usa_temp_seasonality

I would like to plot the seasonality by zipcode for the continental USA. We're going to need a bunch of stuff to do this. Will be using both R and Python.

I also am not entirely sure how I want to do the seasonality calculation. I will bring in Anthro Claude to help with that.

Steps to complete 

R - Use zipcodeR to access all Zipcodes by State and pull out the centroid 

Python - Once I have the zip codes and centroid, will use geopandas and open-elevation to get the elevation for each zip code, this is a requirement for the meteostat python library 

Python - Use meteostat to pull Min and Max daily temperatures per each zip code. Save to Excel 

Python - Use Polars to wrangle and calculate seasonality per zip code 

Unknown - Will need shapefiles for each zipcode, geo_join() with the seasonality 

Python - Plot with Plotly() or something that can do zip codes, color by seasonality and have pop ups (tooltips) for the seasonality score.