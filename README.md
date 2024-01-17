# spotify-data-analysis
Project Overview
This project is focused on analyzing Spotify listening history to explore changes in musical preferences and to build a music recommendation system. The analysis involves examining shifts in music genres and mood pre- and post-pandemic. The recommendation system uses machine learning techniques to suggest similar songs based on user input.

Features
Data Analysis: Analyze changes in music preferences over time, focusing on genres and mood (valence, energy, tempo).
Music Recommendation: Recommend songs that are similar to a user's chosen track based on various musical features.
Data
The project utilizes personal Spotify listening history. The data is divided into two periods:

Pre-pandemic period
Post-pandemic period
Each dataset includes information about the tracks such as 'Track Name', 'Artist Name', 'Valence', 'Energy', 'Tempo', and more.

Setup and Installation
To set up this project, you need to have Python installed along with the following libraries:

Pandas
Scikit-learn
Matplotlib (for data visualization)
Usage
Data Analysis:

Run the data analysis script to see changes in music preferences.
Visualizations include histograms, box plots, and bar graphs.
Music Recommendation:

Use the recommend_song function to input a song name.
The system will output a list of songs that are similar based on the selected features.
