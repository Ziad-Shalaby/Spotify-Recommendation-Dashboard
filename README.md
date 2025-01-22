# Spotify Recommendation Dashboard

## Project Overview

The Spotify Recommendation Dashboard provides an interactive interface for users to explore personalized song recommendations. Built on a combination of scraped and prepared data, this dashboard demonstrates the application of machine learning and similarity analysis for music recommendations. It uses a precomputed similarity file and is designed for ease of use, allowing users to interact with the recommendations directly through the dashboard.

Access the live dashboard here: [Spotify Recommendation Dashboard](https://spotify-recommendation-dashboard.streamlit.app/).

## Table of Contents

1. [Features](#features)
2. [Data Sources](#data-sources)
3. [Installation](#installation)
4. [Usage](#usage)

## Features

- **Interactive Dashboard:** Enables users to input preferences and explore recommended songs.
- **Data Integration:** Combines web-scraped data with a prepared dataset for comprehensive recommendations.
- **Similarity Analysis:** Utilizes a precomputed similarity matrix for fast and accurate results.
- **Streamlit Deployment:** Offers a seamless user experience via a web-based interface.

## Data Sources

1. **Web Scraping:**
   - A script is used to scrape song metadata, including titles, artists, genres, and audio features like tempo, energy, and danceability.

2. **Prepared Dataset:**
   - A pre-curated dataset complements the scraped data, ensuring a rich and diverse set of songs for recommendations.

3. **Similarity File:**
   - A similarity matrix (`similarity.pkl`) is computed using audio features to power the recommendation engine.

## Installation

To run the project locally:

1. Clone the repository:

   ```bash
   git clone https://github.com/Ziad-Shalaby/Spotify-Recommendation-Dashboard.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Spotify-Recommendation-Dashboard
   ```

3. Create a virtual environment and activate it:

   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```

4. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

5. Run the dashboard:

   ```bash
   streamlit run app.py
   ```

## Usage

- Access the dashboard locally by navigating to the URL provided in the terminal after running `app.py`.
- Alternatively, access the live version online: [Spotify Recommendation Dashboard](https://spotify-recommendation-dashboard.streamlit.app/).
