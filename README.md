# sqlalchemy-challenge

# In the jupyter notebook (climate_starter.ipynb), I used sqlalchemy in conjunction with pandas/matplotlib to create two plots to analyse the data provided by the Hawaii Climate database.

# The first plot looked at precipitation over the course of one year between August 23rd, 2016 and August 23rd, 2017. The main difficulty in writing up this code was determining how to collect the data within the range of one year. It was resolved using the timedelta function in the datetime Python module, and would be an important function for subsequent sections of the project. A bar plot visualized the precipitations collected over the aforementioned time frame.

# Temperature was also analyzed further for the station with the most observations (WAIHEE 837.5, HI US, station ID USC00519281). A histogram charted the frequencies of each recorded temperature, showing that the range in temperatures in multiple locations in Hawaii ranged from 60 to 80 degrees Fahrenheit.

# In the API (code found in app.py), I provided the analysis in a JSON format. This allows for users to freely pull out data as they so desire in an approachable format.
