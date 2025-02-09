# Music Data Visualization

## Team Name: Symphony
**Team Member:** Nidhi Vraj Sadhuvala

## Abstract
Music is an integral part of human life, influencing emotions and moods across cultures. This project explores the elements that contribute to a song's popularity, analyzing various musical components such as tempo, loudness, valence, speechiness, and explicit content using a dataset of Spotify Top Hits from 2000 to 2019 sourced from Kaggle. The study aims to provide insights that can help aspiring musicians craft popular music by understanding the trends and correlations between these elements.

## Dataset
**Source:** [Kaggle - Spotify Data](https://www.kaggle.com/code/varunsaikanuri/spotify-data-visualization/data)
- 2000 rows, 18 columns
- Categorical Variables: Artist, Song, Explicit Content, Genre
- Numerical Variables: Duration, Popularity, Danceability, Energy, Loudness, etc.

## Objectives
1. Identify musical elements that contribute to song popularity.
2. Analyze distributions of key variables in the dataset.
3. Understand the trends in music production over the years.
4. Examine correlations between different musical elements.
5. Provide insights for aspiring musicians on composing successful music.

## Data Preprocessing
- Handled missing values and duplicates.
- Converted duration from milliseconds to minutes.
- Extracted primary genre per song.
- Standardized numerical features using MinMaxScaler.
- Added a "Total Songs" column for accurate artist popularity evaluation.

## Visualization Techniques Used
- **Heat Map:** Correlation between different musical elements.
- **Histogram Distribution Plot:** Understanding variable distributions.
- **Radar Chart:** Comparison of elemental values between top and least popular artists.
- **Sunburst Chart:** Hierarchical representation of genres and artists.
- **Scatter Plot & Animated Scatter:** Relationship between energy, tempo, danceability, and popularity over time.
- **Tree Map:** Hierarchical overview of different artists and their associated genres.
- **Funnel Chart:** Comparison of musical values between popular and least popular artists.
- **Box Plot:** Explicit content trends over the years.
- **Bar Chart:** Number of top-hit songs produced per year.
- **Donut Chart:** Proportion of melodic vs. non-melodic content.

## Key Insights
- **Tempo, energy, and danceability** are key factors influencing song popularity.
- **Explicit content** is present in some of the most popular songs, but many top artists avoid it.
- **Pop genre dominates** among the top 30 artists.
- **Higher danceability and energy values** are common in successful songs.
- **2012 had the highest number of hit songs,** possibly due to emerging artists and increased digital accessibility.

## Limitations
- The dataset focuses only on Spotify Top Hits (2000-2019), limiting its applicability to newer trends.
- Music popularity is influenced by external factors such as marketing, social media, and changing listener preferences.
- Trends in music are dynamic, and these insights may not be applicable in the long run.

## Future Work
- Analyze a larger dataset to include a wider range of artists and songs.
- Incorporate machine learning techniques to predict song popularity.
- Examine the impact of social media and streaming algorithms on music trends.
- Conduct sentiment analysis on song lyrics to correlate with musical elements.

## References
1. [Spotify Data Analysis on Kaggle](https://www.kaggle.com/code/goodwanghan/spotify-data-eda-with-fugue-sql-duckdb-and-dask/notebook)
2. [Spotify Popularity Classification Models](https://www.kaggle.com/code/tanakalusengo/spotify-popularity-classification-models/notebook)
3. [Plotly Documentation](https://plotly.com/python/px-arguments/)

## Contributors
- **Nidhi Vraj Sadhuvala**

