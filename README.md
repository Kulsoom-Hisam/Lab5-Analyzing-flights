# **Analyzing Airport Data**

Lab 4 involved analyzing airport data. I used Google Colab for this assingment. I downloaded the airports and airline routes data from OpenFlights Project, explored the data files in Python, created dictionaries and plotted a histogram using these data files.

The first challenge involved importing the airports database into Google Colab and writing a code to print all the airport names of a particular country. Half of the code was already given, the only addition I did was to specify the index and the country in row 3 (I picked Canada) and used the print function to print all airport names in Canada.
The second challenge involved creating a dictionary mapping from an airport ID key to the geographic coordinates. I created two dictionaries- one holding latitudes and the other holding longitudes. 

The third challenge involved calculating geographic distances. I copied and pasted the contents of the geo_distance.py file into a cell on Google Colab. I then ran the cell to define the distance function and used it in subsequent cells. Once I had the distance() function working, I wrote code that reads all the airline routes from the “routes.dat”file, looks up the latitude and longitude of the source and destination airports, and builds a list of route distances.
The fourth challenge involved creating a histogram displaying the frequency of flights by distance. I imported two libraries- numpy and matplotlib for creating a histogram. The first argument I supplied was the dataset (list of distances). The second argument (100) is the number of bins to divide the histogram into. I also specified the color purple for the histogram. 

The histogram output is shown here:

![image of histogram](https://github.com/Kulsoom-Hisam/Lab5-Analyzing-flights/blob/main/histogram.png)
