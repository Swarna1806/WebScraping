# Google Image Scraper

A Python-based tool to **scrape high-resolution images from Google Image Search** using Selenium and BeautifulSoup.

## Features
- Downloads **high-resolution images** by clicking each image container.
- Handles **dynamic page content loading** using Selenium.
- Saves images in a dedicated folder (`imageees`) with incremental numbering.
- Includes error handling for failed downloads or missing elements.
- Automatically verifies **write permissions** before starting.

## Requirements
- Python 3.x
- `selenium`
- `beautifulsoup4`
- `requests`
- Chrome browser
- ChromeDriver (matching your Chrome version)

## Installation
1. Clone this repository:
   ```bash
   git clone <repo-url>
   cd <repo-folder>
