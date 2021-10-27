### cme_datamine_api contains jupyter notebooks that show various ETL and analysis techniques for handling  granular market data from CME's Datamine API's. (This is a work in progress.)

#### Notebook list:
1. download_cme_top_of_book.ipynb:  
 * This notebook contains code to download a 350 megabyte gz file with Top-of-Book records for a single day, and single contract of NYMEX Crude (CL), from the CME website.  
 * The expanded file contains over 6 gigabytes, containing over 85 million Top-of-Book bid/ask quote records from that day.  
 * The notebook then produces 86 csv files with 1 million records in each (except for the last which is smaller).

2. top_of_book_example_data.ipynb:
* This notebook reads the above csv files, and aggregates the data in various ways.