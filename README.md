# Amazon_reviews_scraper

The aim of this webcrawler is to collect all the reviews of a given page. 
Since scraping a product that may have 2000 or more pages of reviews it is advisable to run this program in batches.
Specify the starting and ending webpages and the location where the files need to be saved,
wait for the extraction to end, and then run the tab for stitching all the CSVs once the whole extraction has been finished.
Before running the tab for stitching the CSVs together remember to specify the path where the outputs for a specific product is being saved.

For example if a product review URL looks like this :
```
"https://www.amazon.com/Hunger-Games-Book/dp/0439023483"
```
the program will expect you to create a folder in your Destop like this.
```
/<your_username>/Desktop/Hunger-Games-Book
```
Then you need to specify this in 'output_path' variable.
