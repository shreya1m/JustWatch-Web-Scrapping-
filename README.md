# JustWatch Web Scrapping Project
### Website:
- JustWatch Movies Url-  https://www.justwatch.com/in/movies?release_year_from=2000
- JustWatch Tv Shows Url - 'https://www.justwatch.com/in/tv-shows?release_year_from=2000'


### Overview
This project involves scraping movie and TV show data from JustWatch, a popular platform that aggregates content from various streaming services such as Netflix, Amazon Prime, Hulu, and more. The scraping is achieved using Python, leveraging the Requests library for HTTP requests and BeautifulSoup for HTML parsing. Instead of utilizing JustWatch APIs, we extract information directly from the HTML structure of the website.

### Project Workflow
#### 1. Web Scraping: 
Python scripts make HTTP requests to the JustWatch website and use BeautifulSoup to parse the HTML, extracting relevant movie and TV show details.

#### 2. Data Filtering and Analysis:
The scraped data is processed and filtered using Pandas, allowing for in-depth analysis. This stage involves exploring trends, patterns, and statistics related to the extracted content.

#### 3. Results and Insights:
The analysis provides valuable insights into the available movies and TV shows across different streaming platforms. Results may include popular genres, top-rated content, and other relevant trends.

#### 4. Data Export:
The final results are saved to a CSV file, providing a structured format for easy sharing, further analysis, or visualization.

### Technologies Used
- Python
- Requests library for HTTP requests
- BeautifulSoup for HTML parsing
- Pandas for data manipulation and analysis
### Usage
- Clone the repository to your local machine.
- Run the provided Python scripts to perform web scraping and data analysis.
- Explore the generated CSV file containing the results.
- Feel free to contribute, report issues, or suggest improvements!
