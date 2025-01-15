# UFO Sightings Analysis

This project aims to analyze and explore UFO sightings data over the past century. We investigate various factors such as the location of sightings, the shapes reported, and the sentiment of eyewitness comments.

## Project Goals
- **Data Exploration**: Analyze UFO sightings based on location, duration, and shape.
- **Data Cleaning**: Handle missing data and format issues.
- **Visualization**: Create visualizations such as maps and charts to represent the data.
- **Sentiment Analysis**: Perform sentiment analysis on the comments to understand public perception.

## Files in this Repository:
- `UFO_Sightings_Analysis.ipynb`: Jupyter notebook containing data cleaning, analysis, and visualizations.
- `UFO_Sightings.xlsx`: The raw dataset containing UFO sightings reports.

## Data Overview
The dataset contains columns including:
- `datetime`: The time of the sighting.
- `city`, `state`, `country`: Location of the sighting.
- `shape`: Shape of the UFO reported.
- `duration (seconds)`: Duration of the sighting.
- `comments`: Textual comments from witnesses.
- `latitude`, `longitude`: Coordinates of the sighting.

## Requirements

To run this project, you need the following libraries:
- `pandas`
- `matplotlib`
- `seaborn`
- `folium`
- `wordcloud`
- `textblob`

You can install them via pip:
```bash
pip install pandas matplotlib seaborn folium wordcloud textblob
