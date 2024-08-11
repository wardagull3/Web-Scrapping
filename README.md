# Web Scraping with Python in Google Colab

This repository contains a Python script for web scraping, designed to run on Google Colab. The script demonstrates how to extract data from a website using the `requests` and `BeautifulSoup` libraries.

## Table of Contents

- [Overview](#overview)
- [Setup](#setup)
- [Usage](#usage)
- [Data Extraction](#data-extraction)
- [Contributing](#contributing)
- [License](#license)

## Overview

The provided script scrapes book data from the [Books to Scrape](http://books.toscrape.com) website. It extracts book titles and prices from multiple pages and saves the data to a CSV file.

## Setup

1. Open a new Google Colab notebook.
2. Install the required libraries:

    ```python
    !pip install requests beautifulsoup4
    ```

3. Import the libraries and run the provided code.

## Usage

1. **Clone this repository**:

    ```bash
    git clone https://github.com/yourusername/your-repository.git
    ```

2. **Navigate to the repository folder**:

    ```bash
    cd your-repository
    ```

3. **Open the `web_scraping_colab.ipynb` notebook in Google Colab**:

    You can upload the notebook to Google Colab and run the cells to perform the scraping.

4. **Run the cells** to execute the scraping script. The output will be saved to `books.csv` in the same directory.

## Data Extraction

The script performs the following tasks:

- Sends HTTP requests to the website.
- Parses HTML content using BeautifulSoup.
- Extracts book titles and prices.
- Saves the extracted data to a CSV file named `books.csv`.

## Contributing

If you have suggestions or improvements, feel free to open an issue or submit a pull request. Contributions are welcome!





