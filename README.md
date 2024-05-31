# Billboard Hot 100 Playlist Scraper

This Python script scrapes the Billboard Hot 100 chart from a given date and creates a Spotify playlist with the songs from the chart.

## Prerequisites

Before running the script, you'll need to have the following:

- Python 3.x installed
- `requests` and `beautifulsoup4` Python libraries installed
- A Spotify account
- A Spotify API client ID and client secret (follow the instructions [here](https://developer.spotify.com/documentation/general/guides/app-settings/) to create a Spotify app and obtain the credentials)

## Installation

1. Clone the repository: git clone https://github.com/vedantparmar12/billboard-playlist-scraper.git
2. Navigate to the project directory: pip install requests beautifulsoup4 spotipy
   
## Usage

1. Open the `scraper.py` file and replace the following placeholders with your Spotify API credentials:

```python
CLIENT_ID = 'your-client-id'
CLIENT_SECRET = 'your-client-secret'
Run the script with the desired Billboard Hot 100 chart date: python scraper.py --date=2000-08-12

The script will scrape the Billboard Hot 100 chart from the specified date, create a new Spotify playlist with the songs from the chart, and add the playlist to your Spotify account.
Configuration
You can customize the script's behavior by modifying the following variables in the scraper.py file:

BILLBOARD_URL: The URL of the Billboard Hot 100 chart to scrape
PLAYLIST_NAME: The name of the Spotify playlist to create
PLAYLIST_DESCRIPTION: The description of the Spotify playlist

Contributing
Contributions to this project are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

License
This project is licensed under the MIT License.

This README.md file provides an overview of the project, lists the prerequisites, explains how to install and use the script, and includes sections for contributing and licensing. You can further customize the content based on your project's specific requirements.

