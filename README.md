# Movies-ETL
module 8 


### Overview 

In this module we learned how to extract, transform, and load data. We learned how to do this by helping. We extracted the data from a Wikipedia json file and Kaggle csv file and from there we created data frames out of the files to see what we were working with. Once we created the data frames, they were huge! Looking through these gigantic data frames, there was a ton of data found that we did not need. Through the transform step, we removed columns, rows and null values that were not needed so that we could scale down the information to make it more readable. After cleaning up all the data, we created a final, clean, data frame and load it into a database. In this database we can use SQL to pull certain data points from the master table. 


•	In the first deliverable we extracted the data from Wikipedia, Kaggle and ratings files and converted it to data frames. We did this by creating a function to read all the files in and then created the data frames.

•	In the second deliverable we started the transform process by cleaning the data in each of the data frames created. We created another function to clean the data, remove null values, duplicate columns, etc. 

•	In deliverable three, we continued to clean the data by changing data types, filling in missing values and dropping columns that we do not need. 

•	In deliverable four, we took all the clean data, and created a function to import it into a SQL database. We created a final data frame and printed it out to see what our final clean data table looks like. We are now able to go into the SQL database and manipulate the data as such from there. 

<img width="770" alt="finalDF" src="https://user-images.githubusercontent.com/45208773/137020512-febcb462-099d-4100-b931-99004d9d487c.PNG">
