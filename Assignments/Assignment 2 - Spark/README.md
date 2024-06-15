# Spotify Song Data Analysis

## Project Overview

This project involves analyzing a dataset containing information about songs streamed on Spotify in 2021. The main objective is to clean and preprocess the data, perform specific queries, and implement classification tasks using SparkSQL and SparkDataFrames.

## Dataset

The dataset includes multiple attributes for each song, such as genre, artist, duration, and various audio features like danceability, energy, and valence.

## Tasks

### Data Preparation
1. **Data Cleaning and Engineering:**
   - Handle missing values, duplicates, and perform necessary transformations to make the data usable.

### Queries and Analysis
2. **Implement Queries Using SparkSQL and SparkDataFrames:**
   - **Genre Popularity:** Identify the genre with the highest average popularity.
   - **Artists with Long Songs:** Find artists who have recorded the most number of songs with a duration of more than 5 minutes.
   - **Genre Song Count:** Determine the number of songs in each genre.
   - **Top Artists:** Identify artists who dominated the charts.
   - **Party Songs Recommendation:** Recommend at least 5 fun and energetic songs suitable for a party, using features like energy and danceability.

### Classification
3. **Genre Classification:**
   - Split the data into training and testing sets.
   - Perform classification to predict the genre of each song using SparkML.
   - Apply three different classification methods and compare their accuracies to identify the best classifier.

## Audio Features Provided by Spotify

- **Danceability:** Measures suitability for dancing based on tempo, rhythm, and beat strength.
- **Valence:** Describes the musical positiveness of a track.
- **Energy:** Perceptual measure of intensity and activity.
- **Tempo:** Estimated tempo of a track in beats per minute (BPM).
- **Loudness:** Overall loudness of a track in decibels (dB).
- **Speechiness:** Detects the presence of spoken words in a track.
- **Instrumentalness:** Predicts whether a track contains no vocals.
- **Liveness:** Detects the presence of an audience in the recording.
- **Acousticness:** Confidence measure of whether the track is acoustic.
- **Key:** Estimated overall key of the track.
- **Mode:** Indicates the modality (major or minor) of a track.
- **Duration:** Duration of the track in milliseconds.
- **Time Signature:** Estimated overall time signature of a track.
