# Music Recommender

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)


## Introduction

The Spotify Song Recommender is a Python-based web application that utilizes the Spotify API to suggest similar songs based on the user's input song. The application provides an interactive interface built using Streamlit.

## Features

- Search for a song by its name and year
- Get song recommendations based on the selected song
- Customize the recommendations by selecting specific features
- Visualize the most similar songs using bar plots
- Streamlit web interface for ease of use

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/overlordiam/Music-recommender.git
   cd Music-recommender

2. Create and activate a virtual environment (optional but recommended):

   ```bash
   python -m venv venv
   # On Windows
   venv\Scripts\activate
   # On macOS and Linux
   source venv/bin/activate

3. Install the required packages:

   ```bash
   pip install -r requirements.txt

## Usage

  1. Run the Streamlit app:
     
      ```bash
      streamlit run app.py
  
  3. Access the app by opening the provided URL in your web browser.
  4. Enter the name of a song and the year of its release to get recommendations based on that song.
  5. Select the features you care about and the number of recommendations to be displayed.
  6. Click the "Search for my song" button to check if the song exists in the dataset.
  7. Click the "Get Recommendations" button to view similar songs.

## Credits

- This project uses the Spotify API to retrieve song data.
- The data is stored in a CSV file, which was obtained using web scraping techniques (credit to the original data sources).
- The app is built with Python and Streamlit.

