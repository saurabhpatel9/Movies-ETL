# Movies-ETL
      Extracting data from Wikipedia and Kaggle then transform them using Python(Pandas) and load into PostgreSQL database.

## Summary:
Amazing Prime would like to work further on dataset and wants to keep it updated on a daily basis for better outcome. our client needs to create an automated pipeline that takes in updated data, apply the appropriate transformations, and load the data into existing tables. We refactor the code from this module to create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database.

## Resources:
<ol>
  <li>Python and PostgreSQL </li>
  <li>CSV Files:</li>
<ul><li>ratings.csv</li>
<li>movies_metadata.csv</li></ul>
  <li>JSON File:</li>
<ul><li>wikipedia-movies.json</li></ul></ol>

## Results:
Our client is excited to prepare data for the hackathon where we gather data from both Wikipedia and Kaggle, combine them, and save them into a SQL database so that the hackathon participants have a nice, needed dataset to visualize and do further analysis.Raw data exists in multiple places and needs to be cleaned and structured before it can be analyzed. Using ETL we breaks this problem into three phases: Extract, Transform, and Load. We dealt with two types of data that we are merging; one set comes in a json format that was pulled from wikipedia and two csv files from Kaggle on movie reviews. We followed an iterative process consist of three key steps: plan, inspect, execute that we took within each Jupyter note file. Finally we created dataframe as per our clients request so they can visualize data as per their need.

## Screenshots for count of movies and ratings:
![movies_query](https://user-images.githubusercontent.com/86158802/130849767-c7a0dc3f-362c-4579-a25d-f54caac90978.PNG)
![ratings_queries](https://user-images.githubusercontent.com/86158802/130849774-de44a886-80ed-4d85-8b98-1d9c79ccbd58.PNG)
