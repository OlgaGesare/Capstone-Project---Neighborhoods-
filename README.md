# Capstone-Project---Neighborhoods-

1.	A description of the problem and a discussion of the background. 

Background:
Toronto, the capital of the province of Ontario, is the most populous Canadian city.
Toronto is a well populated areas with businesses thriving. I have always been interested in the hospitality industry and would want to know if I moved to Toronto would I be able to start a restaurant that would thrive and which locations should I consider.

Problem statement:
Problem Statement: For entrepreneurs, find a location for a restaurant can be really hard. An example is chef Nick Liu of College St.’s Dailo. According to an interview he did with The Star in April 2019; he said in the two years it took him to find a location, he lost thousands of dollars, business partners, lived in his car and contemplated leaving the country altogether out of frustration. “Restaurants are a passion project,” he says. “Some people get lucky and make a good living but for the most part you’re looking at one of the worst business models. It was a tough time. It was two years of unemployment, looking for spaces, looking for partners and then losing locations and investors, and having to do it all again.” (Liu, 2019, Finding a location for your restaurant can be harder than you think. From The Star Edition.)

Every year, many Toronto restaurants open and close. The restaurant business is not an easy one to get into, but can be lucrative if your restaurant finds success.
his high-traffic location is expensive, but one of the best areas for visibility. Space downtown is in high demand and is quite costly. When you create a downtown restaurant business, the stakes are high. The first step to rising to the challenges of the fast-paced downtown environment is getting the information you need to succeed.

Main aim of the study is to identify prospectives of a new restaurant that will be close to other businesses and human traffic in Toronto, US. We will analyze the neighborhoods in Toronto to identify the most profitable areas.


Target audience:
a)	Business personnel who wants to invest or open a restaurant. The analysis will beneficial to anyone interested in locating a restaurant in Toronto or opening one
b)	It will highlight the pros and cons of opening a restaurant in Toronto to potential investors and freelancers. 
c)	A new resident in Toronto looking for restaurants to try out. 
d)	Business and Data Analysts/Scientists, who want to implement some of the most used Exploratory Data Analysis techniques to obtain necessary data, analyze it, and, finally be able to tell a story out of it.


2.	A description of the data and how it will be used to solve the problem. 

•	I will need data from the Toronto’s database; census 2016, on the Population, Average income per Neighborhood with Toronto's Neighborhoods shapefile and Foursquare API to collect competitors on the same neighborhoods.
•	I would need to leverage the below data and  Foursquare location data to solve or execute;
Data sources:

I.	Toronto's Census data is publicly available at this website: https://www.toronto.ca/city-government/data-research-maps/open-data/open-data-catalogue/#8c732154-5012-9afe-d0cd-ba3ffc813d5a
II.	Toronto Neighborhoods' shapefile is publicly available at this website: https://www.toronto.ca/city-government/data-research-maps/open-data/open-data-catalogue/#a45bd45a-ede8-730e-1abc-93105b2c439f
III. I will also use the csv file; “https://cocl.us/Geospatial_data”  to get the geographical coordinates of the neighbourhoods.
IV.	To get information on the location and venues in Toronto I will use Foursquare’s explore API. It will give me venues recommendations. I will then collect  their names, categories and locations (latitude and longitude).
V.	From Foursquare API (https://developer.foursquare.com/docs/places-api), I will retrieve the following for each venue:
-	Name of the venue.
-	Category type as defined by the API.
-	Latitude value of the venue.
-	Longitude value of the venue.
