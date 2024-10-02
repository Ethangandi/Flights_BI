Here I've made a dashboard using the 'Flights 2015' dataset from kaggle. Within it I displayed analytics on: flight delays, flight destinations, flight paths, and more between Southwest and American Airlines.

Important: I only used data from the month of December due the the emmense size of the main dataset (5.8 million lines). The main dataset was coupled with another dataset containing info on each airport

Process:
  -imported data
  -made a subset containing data from the month of December and airlines Southwest and American
  -cleaned/reformatted data, changed col names for readability
  -merged the subsetted dataset with the Airports dataframe to add locaiton data for the "destination airport" for each flight 
  -exported dataset to use in Power BI
  -attempted to make a nice dashboard
