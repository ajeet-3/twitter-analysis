PROJECT 


Part 1: Ingesting the Data
The first task is to ingest the tweet data from the TSV files. Here’s how you can approach it:

* Read the TSV Files:
 Concert the TSV file to CSV file for easy understanding , You can use Python libraries like Pandas to read TSV files efficiently.
 Make sure you understand the structure of the data—what columns are available and what each column represents.
* Data Structure:
  Decide on an appropriate data structure to hold the tweet data. Since we want to query the data later, consider using a data structure that allows efficient lookups.
  A common choice would be to create a dictionary or a Pandas DataFrame where each row corresponds to a tweet, and the columns represent tweet attributes (e.g., timestamp, user ID, tweet text, likes, etc.).


  Part 2
Construct functionality that allows you to query the data. If I search for a term, like “music,” I would like to know some subset of the following:
- How many tweets were posted containing the term on each day?
- How many unique users posted a tweet containing the term?
- How many likes did tweets containing the term get, on average?
- Where (in terms of place IDs) did the tweets come from?
- What times of day were the tweets posted at? 
- Which user posted the most tweets containing the term?
