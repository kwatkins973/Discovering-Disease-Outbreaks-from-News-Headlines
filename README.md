# Discovering-Disease-Outbreaks-from-News-Headlines

This is the first part of a python based system to analyse news headlines published around the world for signs of epidemics based on the kind of monitoring the World Health Organisation (WHO) conducts. This first phase of this program as demonstrated in this Python script does the following:

* Reads a test headlines file line by line
* Identifies relevant news headlines
* Extracts the locations (city and/or country name) from each news headline.
* Adds the data to a panda DataFrame.

This script uses 3 alternatives for extracting location names:

* The geonames cache installed locally
* A local instance of MySQL which has had the geonames data installed
* The Geonames services which is accessed using a REST based API call

