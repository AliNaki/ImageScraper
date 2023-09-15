# Flask Web Scraping for Image Search
This Flask-based web application allows users to search for images on Google and download them to a specified directory. Additionally, it stores the downloaded images in a MongoDB database.

## Features
* Search for images on Google.
* Download images to a local directory.
* Store image data in a MongoDB database.

## Installation
1. Clone the repository to your local machine.
```bash
https://github.com/AliNaki/ImageScraper.git
```
2. Install the required Python packages using pip.
```bash
pip install -r requirements.txt
```
## Usage
1. Enter a search query in the provided input field and submit the form.
2. The application will fetch images related to the query from Google.
3. Downloaded images will be saved in a local directory named "images."
4. Image data will also be stored in your MongoDB Atlas database.

## Built With
1. Flask - Web framework
2. BeautifulSoup - Web scraping library
3. pymongo - MongoDB integration

