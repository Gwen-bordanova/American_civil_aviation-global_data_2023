# American_civil_aviation-global_data_2023
Data import, processing and analysis of global data on 2023 civil flights in the US.

I offer you an Analysis of US civil aviation 2023 with a complete dataset containing :
- departure and arrival delays for each flight
- descriptions and delay times
- weather with rain and snow conditions for each airport
- associated airlines
- information for each plane with model and age.
- and finally public holidays

The information on flights comes from the BTS (Bureau of Transportation Statistics) website
and I used the Meteostat Python library to scrape the information. I also developed a correspondence table
for the airports, their identifiers and geolocation coordinates.

The different datasets can be downloaded and used on kaggle.

links :
https://www.transtats.bts.gov/DL_SelectFields.aspx?gnoyr_VQ=FGJ&QO_fu146_anzr=b0-gvzr
https://dev.meteostat.net/
