# Data-Wrangling-with-Pandas

## Data Gathering:
In this project, three sources of data gathered, converted to dataframes, cleaned and combined as master dataframe.
* The first source was csv file.
* The second one scraped from web with requuest and saved as TSV file.
* The last one was taken from tweeter. Data appended to a list, then was written to a text file. After that, the file was read in to a dataframe


## Data Cleaning:
For cleaning step, at first a copy from three dataframes were made to prevent any changes to original data. After that, all points in assess step were cleaned.
* For the first dataframes, all tweets with no retweets recognized and saved in the clean dataframe. Then all data types were corrected and redundant columns were dropped. After that all columns relevant to dog stage, merged to one column.
* For the second and third dataframe, column types were corrected and more clear names were chosen for the columns.
After that, all dataframes were merged and saved in the csv file.After data cleaning, data analysis was done.

