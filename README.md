# Basic Webscraping
## Project Overview
This project focuses on web scraping data from Amazon's list of the top 29 best-selling books. The goal is to extract useful information about each book, such as name of books, author, price and ratings. The collected data can be used for analysis, visualization, or as input for recommendation systems.

## Features
- Extract book details, including:
  - Name of Books
  - Author(s)
  - Price
  - Rating
- Handle pagination to ensure the top 29 books are retrieved.
- Save the scraped data into a structured format (e.g., CSV or JSON).
- Simple and modular code structure for easy updates or customization.

## Requirements
The project requires the following tools and libraries:

- Python 3.7+
- BeautifulSoup (for parsing HTML)
- Requests (for making HTTP requests)
- Pandas (for handling data storage and manipulation)

You can install the required libraries using:
```bash
pip install -r requirements.txt
```

### Sample `requirements.txt` file:
```
beautifulsoup4
requests
pandas
selenium
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/jenishmehta11/Amazon_books_webscraping.git
   cd Amazon_books_webscraping
   ```

2. Run the scraping script:
   ```bash
   python webscraping.py
   ```

3. View the extracted data in the `data/` folder.

## Notes
- **Legal Disclaimer**: Scraping Amazon's website may violate their terms of service. Use this script responsibly and only for educational purposes.
- If Amazon's website structure changes, the scraping script might break and need adjustments.
- Consider adding headers, proxies, and delays between requests to avoid being blocked.

## Future Enhancements
- Add support for more detailed book metadata (e.g., publication date, genre).
- Implement error handling and retry mechanisms.
- Integrate with a database for storing large datasets.
- Add visualization of the scraped data (e.g., top-rated books, price distribution).

## Author
[Jenish Mehta](https://github.com/jenishmehta11)
