# Topos-Assignment
Web Scraping Assignment

### Abstract: <br />
The assignment required me to find and collect data on the top cities based on population in the United States. For my project, I have considered only the top 10 cities in these criteria. Not only have I collected data, which was requested by the assignment but also, I have collected additional information about these cities. Though the data collected by me can be used in a variety of city-wide analysis projects but for the purpose of this project I would like to propose the following objective -

This dataset can be used to determine the livability in the top 10 most populated cities in the United States, to help people decide which city is the best to raise a family. Livability in a city is often tied to availability of physical spaces like parks and green belts, cost of housing/utilities, career opportunities and pollution levels. Moreover, safety, education opportunities as well as health facilities play a major role in determining livability in an area. 

Housing prices and per capita income can be major determinants of livability in a city and therefore I have included both in my dataset. The dataset records violent crime and property crime of cities which determines safety of a city. Here, we can hypothesize that as the number of crimes in a city increases, safety of a place decreases and therefore livability of a place decreases. Higher population is directly related to lesser living space, lower marketplace competition and consequently lower service rates. Also, land area is related to some of the factors mentioned above. Therefore, our hypothesis can be as the population of a city increases, livability decreases because the of the increase in the cost of products and services. Political situation of a city plays a major role in determining the livability of a city and therefore I have included information about the ruling political party in the city in the dataset. Lastly, the dataset can also be used to determine livability based on legal status of recreational cannabis. 

In conclusion, I have tried to create a comprehensive dataset to diagnose the livability of a city. 

### Replication of the results
1. Make sure that **jupyter note book** is installed in the machine where the program is run <br />
2. The following packages are required to be installed before running the program : <br />
  **bs4** - pip install bs4 <br />
  **requests** - pip install requests <br />
  **pandas** - pip install pandas <br />
  **re** - pip install re <br />
  


### Variables:<br />
•	**population rank 2018**: The city rank by population as of July 1, 2018, as estimated by the United States Census Bureau <br />
•	**city**: The city name <br />
•	**state**: The name of the state in which the city lies <br />
•	**estimate_2017**: The city population as of July 1, 2018, as estimated by the United States Census Bureau <br />
•	**census_2010**: The city population as of April 1, 2010, as enumerated by the 2010 United States Census  <br />
•	**change**: The city percent population change from April 1, 2010, to July 1, 2018 <br />
•	**landAreaMile_2016**: The city land area as of January 1, 2016 in sqm <br />
•	**landAreakm2_2016**: The city land area as of January 1, 2016 in km2 <br />
•	**populationDensityMile_2016**: The city population density as of July 1, 2016 (residents per unit of land area) per sqm <br />
•	**populationDensityKm2_2016**: The city population density as of July 1, 2016 (residents per unit of land area) per km2 <br />
•	**latitude**: The latitude of the city <br />
•	**longitude**: The longitude of the city <br />
•	**white**: Percenage of white population in the city  <br />
•	**African American**: Percenage of African American population in the city <br />
•	**Hispanic**: Percenage of Hispanic population in the city <br />
•	**Asian**: Percenage of Asian population in the city <br />
•	**Mayor Name**: The name of the mayor of the city( the party of the mayor is written inside the bracket) <br />
•	**Time Zone**: The time zone the city is present in <br />
•	**Violent Crime**: The number of Violent crimes reported per 100,000 people per year <br />
•	**Property Crime**: The number of Violent crimes reported 100,000 people per year <br />	
•	**House price**: The price of an average house in the city <br />
•	**per capita income**: The avg per capita income of the people in the city <br />
•	**Recreational Cannabis**: Legality of cannabis in the state <br />
•	**life expectancy**: Life expectancy in years <br />
•	**Unemployment Rank**: The rank of the state in terms of unemployment <br />
•	**Educational Rank**: The rank of the state in terms of educational attainment <br />


### URL:

Wiki url = https://en.wikipedia.org/wiki/List_of_United_States_cities_by_population <br />
City url= https://en.wikipedia.org/wiki/ [cityname] <br />
Crime url= https://en.wikipedia.org/wiki/List_of_United_States_cities_by_crime_rate  <br />
House price url= https://www.kiplinger.com/tool/real-estate/T010-S003-home-prices-in-100-top-u-s-metro-areas/index.php   <br />
Income url = https://www.forbes.com/sites/jacquelynsmith/2013/11/27/the-u-s-cities-where-people-earn-the-biggest-and-smallest-paychecks/#7a4324283b0d <br />
Cannabis url = https://en.wikipedia.org/wiki/Legality_of_cannabis_by_U.S._jurisdiction <br />
Life Expectancy url =  https://en.wikipedia.org/wiki/List_of_U.S._states_and_territories_by_life_expectancy <br /> 
Education url = https://en.wikipedia.org/wiki/List_of_U.S._states_by_educational_attainment <br />
Unemployment Rate url = https://www.bls.gov/web/metro/laummtrk.htm <br />

