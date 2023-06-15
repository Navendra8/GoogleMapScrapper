Google Maps Business Scraper
This script allows you to scrape business data from Google Maps search results using Selenium. You can search for businesses in a specific city and query and retrieve information such as address, phone number, name, rating, and website URL.

Prerequisites
Python 3.x
Selenium
pandas
Make sure to install the required dependencies by running the following command:

Copy code
pip install selenium pandas
You also need to download the ChromeDriver executable for your specific Chrome version and provide its path in the code.

Usage
Clone the repository:
bash
Copy code
git clone https://github.com/your-username/google-maps-business-scraper.git
Navigate to the project directory:
bash
Copy code
cd google-maps-business-scraper
Run the script:
Copy code
python scraper.py
Enter the name of the city where you want to search for businesses.

Enter the query for the type of business you are interested in.

Wait for the script to scrape the data. It will display the page number as it progresses.

Once the scraping is complete, the data will be saved to an Excel file named <city>_<query>.xlsx.

Open the Excel file to view the scraped data.

Disclaimer
Scraping data from Google Maps or any website may be against the website's terms of service. Use this script responsibly and make sure to comply with any legal and ethical requirements. The developer is not responsible for any misuse or violation of terms of service.

Feel free to contribute to the project by submitting bug reports, feature requests, or pull requests.
