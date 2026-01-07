# Spotify Dashboard 2025

### An dashboard helping DJs and mixers discover their next perfect track

---

## Overview

This data science dashboard analyzes audio features and track characteristics to help DJs and music mixers find the ideal next song for their sets. Built using a comprehensive Spotify dataset and powered by the Deezer API, the tool leverages music metadata to suggest tracks that flow seamlessly together based on tempo, energy, key, and other musical attributes.

## Features

### Smart Track Discovery
Find compatible songs based on musical characteristics like BPM, key, and energy levels

### Audio Feature Analysis
Analyze tracks across multiple dimensions including danceability, valence, acousticness, and instrumentalness

### Mix Compatibility Scoring
Get recommendations ranked by how well tracks will blend in your DJ set

### API Integration
Real-time data using the Deezer API for extended track information

---

## Project Structure

```
Spotify-Dashboard-2025/
├── apiexplorer.py          # API interaction and data exploration utilities
├── spotify_api.py          # Core Spotify/Deezer API integration
├── spotify_songs.csv       # Dataset of 30,000+ Spotify tracks with audio features
└── README.md               # Project documentation
```

---

## How to install

```bash
git clone https://github.com/Kaiking28/Spotify-Dashboard-2025.git
cd Spotify-Dashboard-2025
python spotify_api.py
```

## Dataset

This project uses the [30,000 Spotify Songs dataset](https://www.kaggle.com/datasets/joebeachcapital/30000-spotify-songs) from Kaggle, which includes comprehensive audio features for track analysis.

