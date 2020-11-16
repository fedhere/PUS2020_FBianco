# Motivation:
One of the things that make NYC so interesting to study is its diversity on many axes: ethnic, economic, cultural. Neighborohoods tend to be segregated and clustered on most socioeconomic characteristics, however these characteristics do evolve in time. The goal is to identify NYC neighborhoods that are homogeneous by clustering their socioeconomic characteristics in 2000, and in 2010, and find the neighborhoods that change cluster, indicating that they evolve differently with respect to their cluster peers (e.g. gentrification).

# Method:
work at the maximum granularity that the data allows.


1) Find the number of businesses in 2010 and 2000. This information is available at the zipcode level (see helper notebook in this repo NYC_business_census_data.ipynb and DATA.md).

2) Gather a zipcode shapefile and merge the number of businesses with the zipcode shapfile so as to obtain a geodataframe 

3) Find the density of businesses by dividing the number of businesses by the area of the zipcode (remember the geospatial homeworkm HW3 and HW4 and the geospatial lab) and show them the density in a choroplath (a heatmap version of a geographical map where each zipcode (census tract later) is a different color based on the value of the feature you are mapping) for 2000 and 2010 (OPTIONALLY: also show the difference in business density between 2000 and 2010 in a map, this will help you make sure you are on the right track) - see notes on this in DATA.ipynb

4) Collect census data from the 2010 and 2000 census and extract the estimate (mean or median) age, population, and diversity of each census tract for all 5 NYC boroughs. The diversity (or lack thereof) can be measured by the fraction of white population.

5) Collect the income data by census tract from the income from American Fact Finder for the years 2010 and 2000 at the census tract level.

6) Merge the census datasets for each year and show a the tables containing the relevant data: the features and whatever else you need to identify and plot the data.

7) Merge the df with the census tracts shapefile so as to obtain a geodataframe (see DATA and HINTS files) and display each of your features as a choropleth for both 2010 and 2000, and show the difference in the features as a third choroplath.

8) Aggregate the census four features at the zipcode level and merge the zipcode dataframe - see helper notebook spatial_joint_of_census_tracts_and_zipcode.ipynb

9) Merge all zipcode level df

10) Cluster the census tracts on these four features (using a Eucledian distance and choosing whichever clustering model you want). Remember that before whitening you have to whiten (or standardize) the data

11) Identify the census tracts that have changed cluster assignment (those that are now associated with a different group of census tracts) and show a choropleth of the clusters in 2010, 2000 and a choropleth of the cluster changes. (Once you get through this, you have done most of the heavy lifting! The rest is building upon this work.)

12) Define a function that given a dataframe containing the relevant information and two cluster labels finds if the census tract changed cluster assignments from the first to the second label, and if so finds the individual features that are significantly different as measured by Pearson's correlation, plot those zip codes, and plot a histogram of the features that have significantly changed. Run your function for all label pairs (2 points, one for the identification of locations that changed cluster and one for the identifiation of the features that changed significantly).

13) Comment on the strength and weaknesses of this analysis, and on your findings (this is not the last step, but comments should be given throughout the notebook, and summarized here).

OPTIONAL: cluster with a different algorithm and see if things change.

DATA:
the data is described in the DATA.md markdown.

