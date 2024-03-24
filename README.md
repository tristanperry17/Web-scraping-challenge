# Web-scraping-challenge

This repository contains two notebook files:
  1.) part_1_mars_news.ipynb
      
  2.) part_2_mars_weather.ipynb

Both notebooks make use of splinter, which allows the user to open a browser (Chrome) to explore web pages provided within the code. The html of the websites is parsed and scraped for relevant data. In part 1, both the article titles and headers are scraped and stored. In part 2, a table of data is scraped and stored in a DataFrame, from which the data can easily be analyzed using Pandas. Part 2 also exports the new DataFrame into the output file, 'temp_data.csv', located in the 'Output' directory. 
