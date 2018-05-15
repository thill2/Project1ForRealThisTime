# GroupProject1-v2
*Searching for jobs close to home*

This project was to learn how to **combine 2 API calls**.  We chose to use **Google Maps and the Ziprecruiter API**.  Both of these API's have constraints which make this project hard to maintain without paying for these API services.  The Google Maps API has a maximum number of calls that can be made every 24 hrs.  The Ziprecruiter API keys are only distributed to approved users.  They were gracious enough to give us a temporary API key to use, however at this time it no longer functions.

In the apps prime, users could input their address and a title or descriptor of the types of jobs they're looking for.  The map then diplays a pin on the users home addres, and queries Ziprecruiter for jobs with that particular keyword in the nearby area.  

We then took the first 10 company names from the Ziprecruiter JSON, searched for those names in the Google Maps API, and displayed pins at the locations of those companies.  

The app also displayed the company names and job titles from the Ziprecruiter API in an unordered list to the left of the map.

The idea was to make an interface similar to Zillow so users could look at company locations on a map when comparing potential employers. 
