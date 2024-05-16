# web_scrapping_from_iplt20

## IPL Stats Scraper

This is a Node.js script that uses Puppeteer to scrape player stats from the official IPL website (iplt20.com). It retrieves the top 10 players for the following categories:

- Orange Cap (most runs scored)
- Most fours
- Most sixes 
- Most fifties
- Most centuries

The script saves the scraped data to a JSON file named "iplData.json" for each IPL season.

### Prerequisites

- Node.js installed on your system
- Puppeteer library installed via npm

### Installation

1. Clone the repository or copy the script file to your local machine.
2. Open a terminal and navigate to the directory containing the script.
3. Run `npm install puppeteer` to install the Puppeteer library.

### Usage

1. Run the script using Node.js:

    ```bash 
    npm start
    ```

### Script Modification for Specific Seasons

When scraping data, the script allows for retrieving information for specific IPL seasons by adjusting the value of the `iplSeasonNumber` variable. Here's how the variable corresponds to the IPL seasons:

- Setting `iplSeasonNumber` to 1 retrieves data for the latest season season.
- Setting `iplSeasonNumber` to 2 retrieves data for the season before the latest one.
- Adjust the value accordingly to scrape data for different IPL seasons.