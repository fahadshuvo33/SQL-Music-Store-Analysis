# Music Store Data Analysis

This project involves analyzing data from a music store database using SQL with MySQL. The database consists of several tables, including customers, invoices, artists, albums, tracks, genres, media types, playlists, playlist tracks, and employees. 

In addition to the original files mentioned in the instructions (customers.csv, invoices.csv, and invoice_line.csv), this project also includes the following CSV files:
- `employees.csv`: contains information about the employees of the music store
- `media_type.csv`: contains information about the different media types for music tracks
- `playlist.csv`: contains information about the playlists in the music store
- `playlist_track.csv`: contains information about the tracks in each playlist

## Installation and Dependencies

To run this project, you will need to have MySQL installed on your computer. You can download and install it from the official website: https://www.mysql.com/downloads/

You will also need to have a MySQL client installed. If you're using a Mac, you can use the built-in Terminal application. If you're using Windows, you can use the Command Prompt or Windows PowerShell.

## Usage

To use this project, first, clone the repository to your local machine:

~~~bash
git clone https://github.com/fahadshuvo33/SQL-Music-Store-Analysis.git
~~~
Then, navigate to the project directory:
~~~bash
cd SQL-Music-Store-Analysis
~~~
To create the database and tables, run the following command:
~~~bash
mysql -u <username> -p < database.sql
~~~
Replace <username> with your MySQL username, and enter your MySQL password when prompted.

To import the data from the CSV files into the tables, run the following command:
~~~bash
mysqlimport -u <username> -p music_store <file_name>.csv
~~~
Replace <username> with your MySQL username, and enter your MySQL password when prompted. Replace <file_name> with the name of the CSV file you want to import.

Once you have imported the data, you can start querying the database using SQL. The queries for the project are located in the queries.sql file. To run the queries, use the following command:

~~~bash
mysql -u <username> -p music_store < queries.sql
~~~
Replace <username> with your MySQL username, and enter your MySQL password when prompted.

## Conclusion

This project demonstrates how to analyze data from a music store database using SQL with MySQL. By importing CSV files into a MySQL database, you can easily query the data and extract insights that can inform business decisions.

