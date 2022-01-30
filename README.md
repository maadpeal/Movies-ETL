# Movies-ETL

## Purpose
    -  The purpose of this script is to prepare the Amazing video data for
    then be analyzed later, it is sought in the first instance to create
    an approximation to what the ETL process would be.

## Step of Etl
    - In this case, you must first read the given files, which in this case
    it would be two csvs and one json.
    - Then, the general structure of the loaded data is reviewed.
    - It tries to load a dataframe and see if it can be done and what structure it forms.
    - The first thing that was done was to treat the data of the json file that had a
    more complex structure than those of the csvs, since these csvs came from
    a kaggle repo that in theory was treated to upload it to the page.
    - The one from the json proceeds to eliminate the series to only analyze the movies.
    - Then excess columns are eliminated and the types that are needed are changed.
    - We proceed to inspect the data loaded from kaggle and check if there is
    some column or row that needs treatment.
    - Then proceed to merge all the data by their respective ids.
    - It is finally decided which date to keep from wikipedia and which from kaggle.
    - Finally, the postgres database is loaded into their respective tables.

## Results
    - We can see the data loaded in their respective postgres tables (image A-1,B-1)