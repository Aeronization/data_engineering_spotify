# data_engineering_spotify
ETL process using the Spotify API.

## Description
Will get the last 24 hours of information from a Spotify account using the Spotify API. The information will be validated then can be saved in the database of choice. Locally we will use the sqlite3 database, however using an online solution via AWS/GCP will be ideal.

## Production Environment
I would recommend using Google Cloud Platform.
1) Create a new virtual machine instance.
2) SSH into this new instance.
3) Copy/Paste main.py code into SSH terminal and save to a google storage instance (MySQL).

## Additional Recommendations
Google CLoud Scheduler might be an optimal solution. Will investigate.
