# zip code shape file
https://data.cityofnewyork.us/Business/Zip-Code-Boundaries/i8iw-xf4u/data?no_mobile=true

# census tract shape file
https://data.cityofnewyork.us/City-Government/2010-Census-Tracts/fxpq-c8ku

# businesses

ftp://ftp.census.gov/Econ2001_And_Earlier/CBP_CSV/zbp00totals.zip
ftp://ftp.census.gov/econ2010/CBP_CSV/zbp10totals.zip

See [this notebook](NYC_business_census_data.ipynb) to read these data in 

When you plot them in a choropleth you may not be able to see a lot ... there are some **extremely** small zipcodes in NYC that are skeweing the density of businesses. 
Remove these outliers. 

# Census data
we have already worked with the census data in DE, see 
