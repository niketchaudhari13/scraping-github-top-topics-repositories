# Project Title : Scraping Top Repositories for Topics on Github
Problem Statement :

- Scrape the list of topics on https://github.com/topics and fetch its topic title , topic page url and topic description.
- For each topic fetch its top 30 trending repositories with repository name , username , stars and its repository url.
- And at last create the topic csv files residing under a single folder.


Steps Followed :

- As mentioned in problem statement scraped respective url i.e " https://github.com/topics".
- Getting all the list of topics. For each topic getting its topic title , topic page url and topic description.
- For each topic ,getting all top 30 trending repositories from its topic page.
- For each repository getting its repository name , username , stars and its repository url.
- For each topic creating a CSV file for it.
- Storing all csv files under a single folder

Tools used : Python , requests , Beautiful Soup , Pandas

Repository holds :

code file
- code documentation file (explaing the project , idea , working of functions , future works and references)
readme file

Point to be noted :

- Code also has a function documentation of it , kindly refer for understanding.
