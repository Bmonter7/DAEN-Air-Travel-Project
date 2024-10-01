# Air Travel: Pre-Pandemic vs Post-Pandemic 
The objective of our data analysis project is to show how the air travel industry as a whole was impacted by the COVID-19 pandemic, which brought the world to a halt in the middle of March 2020. 

We will take a look at how many passengers were still flying, how many passenger flights were still in the air, how many cargo flights were still in the air, and how each airline was impacted alone. 

Through different data visualization and data analysis techniques, we will model and display the data to show that the air travel industry was negatively impacted during March 2020. 

Packages needed (pip install):

- pandas
- datetime
- geopandas
- keplerGl
- matplotlib
- numpy
- sklearn
- bar_chart_race

ffmpeg: We followed the instructions in this link: https://superuser.com/questions/624561/install-ffmpeg-on-os-x

Data needed:
- Flights: https://zenodo.org/record/6078268/files/flightlist_20200301_20200331.csv.gz?download=1
- Airlines: http://www.lsv.fr/~sirangel/teaching/dataset/airlines.txt
- Airports: http://www.lsv.fr/~sirangel/teaching/dataset/airports.txt
- Aircrafts: http://www.lsv.fr/~sirangel/teaching/dataset/aircrafts.txt

For Airlines, Airports and Aircrafts the author used \N to signify null values but this is read as new line in python. To fix this we opened each file in text edit and replaced all \N with N/A.

Once the required packages are installed and all data is collected, click run all cells in jupyter and explore our analysis!
