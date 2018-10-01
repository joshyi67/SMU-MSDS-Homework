# Purpose

Homework assignment work detail:
  * Data Munging
  * Data Merging
  * Data Summary
  * Github Upload
 
# Sources

Shown in order as seen on homework:
  * yob2016
    - text file
  * yob2015
    - text file
  * Baby_girlname
    - csv file

Other sources:
  * https://stackoverflow.com/questions/28873141/view-an-entire-dataset-in-rstudio-past-1000-row-limit
  * https://www.r-bloggers.com/r-sorting-a-data-frame-by-the-contents-of-a-column/
  * https://lembra.wordpress.com/2010/03/12/adding-new-column-to-a-data-frame-in-r/
  * https://www.statmethods.net/management/sorting.html
  * http://rprogramming.net/write-csv-in-r/
  
# Material
  * RMD file
  * Raw csv file for "Baby_GirlNames"
  * MD file
  * HTML file
  * orignal text file

# Definitions of Objects
  * df - variable that holds the read text file from the designated file path
  * y2016 - variable removes the duplicate/error from the df table
  * y2015 - variable reads the yob2015 text file from the designated file path
  * final - variable merges the two variable tables y2016 and y2015
  * sort.final - variable that sorts the "Total" column in descending order
  * filter.final - variable excludes all Males from the sort.final table
  * top.final - variable that gives the top 10 of girl names
  * csv.final - variable only pulls in the baby name and the total columns
