# yun-nlp-assignment

## Overview
This Python script serves as a solution for fetching data regarding Reliance Industries Ltd. (RIL) from various sources including Twitter, news websites, and other public internet mentions within the last 24 hours. The extracted data is structured as a list of dictionaries, with each dictionary containing information about the source URL and the scraped text.

## Usage
To utilize this script, follow these steps:
1. Ensure Python is installed on your system.
2. Install necessary libraries using `pip install requests beautifulsoup4`.
3. Run the script with the provided Python code.
4. The script will fetch data from different sources and structure it as specified.

## Methodology
The script employs web scraping techniques to extract data from various online platforms. Initially, attempts were made to extract data from Twitter using Selenium, but encountered blocking issues. API usage was explored, but abandoned due to limited filtering capabilities. Ultimately, data extraction was performed from the news section of Google and Google News.

## Note on Data Extraction
To extract posts from Twitter, I initially thought to use Selenium but faced blocking issues. API usage was considered but abandoned due to limited filtering capabilities. Consequently, data extraction was conducted from the news section of Google and Google News.

## Output Format
The final output is structured as a list of dictionaries, with each dictionary containing the following keys:
- `url`: The source URL where the data was scraped.
- `headings`: The scraped headings
- `paragraphs`: The scraped and filtered paragraphs in news articles

## Limitations
- The script may encounter limitations in extracting data from dynamic or heavily JavaScript-based websites.
- Due to the nature of web scraping, there may be restrictions imposed by websites on the frequency and volume of requests.

Feel free to modify the script to suit your specific scraping needs or to integrate additional functionality as required. If you encounter any issues or have suggestions for improvements, please feel free to contribute or reach out.
