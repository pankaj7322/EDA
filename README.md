## Exploratory Data Analysis
### About Dataset
#### Context
I really get fascinated by good quality food being served in the restaurants and would like to help community find the best cuisines around their area

#### Content
Zomato API Analysis is one of the most useful analysis for foodies who want to taste the best cuisines of every part of the world which lies in their budget. This analysis is also for those who want to find the value for money restaurants in various parts of the country for the cuisines. Additionally, this analysis caters the needs of people who are striving to get the best cuisine of the country and which locality of that country serves that cuisines with maximum number of restaurants.♨️

For more information on Zomato API and Zomato API key
- Visit : https://developers.zomato.com/api#headline1
- Data Collection: https://developers.zomato.com/documentation

Data
Fetching the data:
- Data has been collected from the Zomato API in the form of .json files(raw data) using the url=https://developers.zomato.com/api/v2.1/search?entity_id=1&entity_type=city&start=1&count=20
- Raw data can be seen here

Data Collection:
Data collected can be seen as a raw .json file here

Data Storage:
The collected data has been stored in the Comma Separated Value file Zomato.csv. Each restaurant in the dataset is uniquely identified by its Restaurant Id. Every Restaurant contains the following variables:

- Restaurant Id: Unique id of every restaurant across various cities of the world
- Restaurant Name: Name of the restaurant
- Country Code: Country in which restaurant is located
- City: City in which restaurant is located
- Address: Address of the restaurant
- Locality: Location in the city
- Locality Verbose: Detailed description of the locality
- Longitude: Longitude coordinate of the restaurant's location
- Latitude: Latitude coordinate of the restaurant's location
- Cuisines: Cuisines offered by the restaurant
- Average Cost for two: Cost for two people in different currencies 👫
- Currency: Currency of the country
- Has Table booking: yes/no
- Has Online delivery: yes/ no
- Is delivering: yes/ no
- Switch to order menu: yes/no
- Price range: range of price of food
- Aggregate Rating: Average rating out of 5
- Rating color: depending upon the average rating color
- Rating text: text on the basis of rating of rating
- Votes: Number of ratings casted by people

#### Acknowledgements
I would like to thank Zomato API for helping me collecting data


#### Inspiration
Data Processing has been done on the following categories:
Currency
City
Location
Rating Text

