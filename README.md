# spotify-recommendation-system
used:Music Recommendation System using Spotify Dataset

# Music Recommendation System using K-Means Clustering

This project implements a **Music Recommendation System** using **K-Means Clustering** on the **Spotify Dataset**. The system recommends songs based on the songs you like, using a clustering algorithm to group similar songs together.

## Project Overview

The goal of this project is to recommend songs to users based on their preferences using **K-Means Clustering**. The system works by analyzing various features of songs (such as `danceability`, `energy`, `tempo`, etc.) and clustering them into groups. When a user provides a list of songs they like, the system recommends songs from the same cluster that match their preferences.

### Key Features:
- **Song Clustering**: The dataset is processed using **K-Means clustering**, where songs with similar features are grouped together.
- **Song Recommendation**: Based on user input (songs they like), the system recommends songs from the same cluster.
- **Spotify Dataset**: The system uses the Spotify dataset, which includes song features like `danceability`, `energy`, `loudness`, and `tempo`.

## Datasets Used

The project uses the following CSV files from the Spotify dataset:

1. `data.csv` - Contains basic song information and features.
2. `data_by_artist.csv` - Contains song data grouped by artist.
3. `data_by_genres.csv` - Contains song data grouped by genre.
4. `data_by_year.csv` - Contains song data grouped by year.
5. `data_w_genres.csv` - Contains song data with genre information.

## Algorithm Used

The **K-Means Clustering** algorithm is used to group songs based on their features. The key steps in the algorithm are:

1. **Preprocessing**: Clean the data and normalize the song features.
2. **K-Means Clustering**: Apply the K-Means algorithm to group songs into clusters based on their features.
3. **Recommendation**: Given a set of songs the user likes, recommend other songs from the same cluster.

