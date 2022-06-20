# Spotify_music_trends


Link to blog - https://www.kaggle.com/code/hkapoor/music-trends-analysis-by-location

![Spotify_App_Logo](https://user-images.githubusercontent.com/37941871/170857159-4b4b76d4-693e-4d0b-a577-9e1bb1f9d029.svg)

## Libraries Used
<ul>
  <li>pandas==1.4.2</li>
  <li>numpy==1.21.6</li>
  <li>matplotlib==3.5.1</li>
  <li>seaborn==0.11.2</li>
</ul>

## Project Motivation
People in different parts of the world prefer to hear songs of different kinds, genres and duration. Spotify is one place where most of them fulfil their music cravings. In this notebook, we will perform a simple EDA of music trends around the globe. Here, we will be using <b>Spotify's Top Songs by Country Charts</b> dataset which was extracted by me using Selenium and BeautifulSoup and is available on Kaggle <a href="https://www.kaggle.com/hkapoor/spotify-top-songs-by-country-may-2020">here</a>. I also gave the charts a Spotify coloured theme.

## File Description
Please find the code in the Jupyter notebook - <b>music-trends-analysis-by-location.ipynb</b>
<br>
and the data here - <b>Data\SpotifyTopSongsByCountry - May 2020.csv</b>

## Summary
<ul>
  <li>Dataset is imbalanced with more Europian countries.</li>
  <li>Some songs have managed to make in 96% of Top Charts.</li>
  <li>Even though some artists have occurances in the Top charts, they don't have any song in Top 10 tracks occurances.</li>
  <li>Average song duration preferred by most is around 3:00 minutes to 3:20 minutes.</li>
  <li>People in Asian countries prefer longer song duration. Europian countries mostly listen to songs close to or less than 3 minutes.</li>
  <li>Asian countries prefer less of explicit songs, only 18%, compared to world average of 35%.</li>
  <li>"Global Top 50 Chart" has 23 explicit songs.</li>
</ul>

## Acknowledgements
#### Data Source - https://www.kaggle.com/hkapoor/spotify-top-songs-by-country-may-2020
