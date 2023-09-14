# web-scraping-challenge

Scraping table data and other element information from websites containing data on Mars

Contributor: Brian Kath

Repository structure:

 	- Main folder
		- .gitignore
		- README.md
		- article_info.json
		- mars_data.csv
		- part_1_mars_news.ipynb
		- part_2_mars_weather.ipynb

Overview:

This project contained two parts. For the first part, I used Splinter and Beautiful Soup to automatically visit a web page containing articles related to Mars and scrape the article title and preview for each article on the page. I then converted the scraped data into a Python dictionary and exported the data into a JSON file.

For the second part of the project, I used Splinter and Beautiful Soup to automatically visit and scrape a webpage containing a table with various Mars data. I then stored the data in a Python list, which I then converted to a Pandas DataFrame. I converted the data to appropriate data types so I could analyze it better, and I created several plots using Matplotlib to illustrate different aspects of the data (i.e., average temperature by month, average pressure by month, etc.). Finally, I exported the finished DataFrame to a csv file.