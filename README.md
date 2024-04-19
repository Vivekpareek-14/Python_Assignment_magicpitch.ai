# Python_Assignment_magicpitch.ai

This Python script is designed to scrape restaurant data from the Yellow Pages UAE website. It extracts information such as restaurant names, locations, contact details, and more, and saves it into a CSV file for further analysis.

#Instructions

1. Clone Repository: Clone this repository to your local machine.
   `git clone <repository_url>`

2. Install Dependencies: Ensure you have Python installed on your machine. Install the required dependencies using pip.
   `pip install -r requirements.txt`
3. Run the Script: Execute the Python script "Assignment_magicpitch.ipynb" using Python.
   `python3 Assignment_magicpitch.ipynb`
4. View Results: Once the script completes execution, you will find the scraped data saved in a CSV file named restaurant_data.csv in the same directory as the script.

#Script Details
- Base URL: The script starts scraping from the base URL specified (https://www.yellowpages-uae.com/uae/restaurant).
- Pagination Handling: It automatically detects and handles pagination to scrape data from multiple pages until a predetermined number of entries is reached.
- Data Extracted: The scraped data includes restaurant names, locations, cities, regions, postal codes, phone numbers, mobile numbers, company page links, and logo URLs.

#Notes
- Ensure a stable internet connection while running the script to prevent interruptions in data scraping.
- You may customize the script according to your specific requirements, such as adjusting the target number of entries or modifying the data fields to be scraped.
- Running the script may take some time depending on the number of pages being scraped and the internet connection speed.
