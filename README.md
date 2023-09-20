# Similar Song Finder

## Introduction

Welcome to the Similar Song Finder project! This project is a simple Python-based tool that helps you find the most similar song to a given song in a dataset. It uses a variety of musical attributes such as valence, acousticness, danceability, energy, instrumentalness, speechiness, and tempo to calculate the similarity between songs.

## Project Description

This project consists of a Python script contained in an Jupyter Notebook (`similar_song_finder.ipynb`) and a dataset (`songs_dataset.csv`) containing information about various songs. The script provides a function to find the most similar song to a given song name within the dataset.

## Dataset

The dataset (`songs_dataset.csv`) contains the following columns:
- `id`: Song ID
- `name`: Song name
- `valence`: Valence of the song
- `acousticness`: Acousticness of the song
- `danceability`: Danceability of the song
- `energy`: Energy of the song
- `duration_ms`: Duration of the song in milliseconds
- `explicit`: Whether the song contains explicit content (0 or 1)
- `instrumentalness`: Instrumentalness of the song
- `key`: Key of the song
- `popularity`: Popularity score of the song
- `release_date`: Release date of the song
- `speechiness`: Speechiness of the song
- `tempo`: Tempo of the song
- `artists`: Artists who performed the song
- `year`: Year in which the song was released

## Getting Started

To use this project, you'll need to have Python installed on your system. You can also use a Jupyter Notebook environment to run the `similar_song_finder.ipynb` script. Additionally, make sure you have the dataset `songs_dataset.csv` in the same directory as the script.


## Functionality
This project notebook provides the following functionality:

  -> Loading and preprocessing of the dataset.
  -> Calculation of song similarity based on various musical attributes.
  -> Finding the most similar song to a given song name.
  -> Displaying the most similar song's name, similarity percentage, and artist information.
