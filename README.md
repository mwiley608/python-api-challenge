# python-api-challenge
Bootcamp module 6 challenge uses Python, Pandas, and API keys. The script in WeatherPy.ipynb generates 500 cities at random using citipy, then pulls the weather data for each city from OpenWeatherMap API. Specifc weather attributes in the data are anlyzed based on their correlation to lattitude and later they are split between the northern and souther hemispheres.  

In VacationPy.ipynb the randomly generated list is narrowed down based on ideal weather conditions to pinpoint possible vacation destinations. The cities were plotted on a map with a corresponding hotel within 10,000 meters of the city coordinates. 

References Data Source: Data generated by CitiPy Python library and OpenWeather Map API

I used the provided WeatherPy_starter.ipynb and VacationPy_starter.ipynb files located in the Resources folder as a guide for my script. It included blocks of starter code as well as instructions, and I used the style and structure for my script. 

To determine how to add gridlines to scatter plots I referenced the webpage: https://stackoverflow.com/questions/20616754/pandas-how-to-display-minor-grid-lines-on-x-axis-in-pd-dataframe-plot

For additional information on how to copy a dataframe with specific columns, I referenced the webpage https://sparkbyexamples.com/pandas/pandas-create-new-dataframe-by-selecting-specific-columns/

On August 9, 2023, I used the Ask BCS resource to assist because my script was not finding hotel information. They instructed me on how to correct my script as I was using the incorrect category label "hotel" instead of "accommodation.hotel".
