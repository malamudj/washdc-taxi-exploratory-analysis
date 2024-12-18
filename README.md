# Washington DC Taxi Exploratory Analysis
This project provides a workflow to complete an exploratory data analysis of Washington DC taxi data that is publicly available from Open Data DC. Three different notebooks are provided that focus on reading and inspecting data, plotting visualizations, and mapping geospatial data. <br><br> As an analyst with the Washington DC Department of For-hire Vehicles (DFHV), I wanted to share tools that can quickly identify trends in trip activity and provide insights about the taxi industry. 


## Project Details:

**Language used:** Python

The first notebook focuses on reading files from a web download, concatenating separate files into a single dataframe, and inspecting the data for null values and column correlation. The Pandas library is used to read in the data. Matplotlib is used to visualize the data inspection process. <br><br> The second notebook provides options for plotting visualizations that show temporal trends using different dimensions of the trip data. After an initial analysis reveals trip records with irregular data, steps are provided to clean the dataset for a more accurate analysis. <br><br> The third notebook introduces mapping techniques to show the location of individual trips and to group trips by zip code and join them to a polygon layer. The Geopandas library is utilized in this notebook to analyze and map geospatial data.


