**Computational Musicology – Playlist Analysis**

This project analyzes a personal Spotify playlist consisting of 101 favorite songs across multiple languages (Dutch, English), genres (rap, trap, R&B, pop), and artists (e.g., The Weeknd, Michael Jackson, Frenna).

Although the playlist appears stylistically diverse, feature-based analysis reveals structural consistencies.

**Correlation Analysis**

A correlation matrix of Spotify audio features (danceability, energy, valence, acousticness, etc.) shows strong relationships between energy and loudness, and moderate clustering of danceability across genres. This suggests that emotional intensity and rhythm play a stronger role in musical preference than genre labels.

**Self-Similarity Matrix**

A feature-based self-similarity matrix reveals block structures, indicating clusters of songs with similar timbral and rhythmic characteristics. Despite genre differences, many tracks share comparable energy-valence profiles.

**Interpretation**

The analysis suggests that musical preference may be organized around mood and sonic intensity rather than genre. This explains how artists as different as Michael Jackson and modern trap artists coexist within the same preference structure.

## Correlation Analysis

![Correlation Matrix](correlation_matrix.png)

The correlation matrix shows a strong positive correlation between **Energy and Loudness (r = 0.75)** and a strong negative correlation between **Energy and Acousticness (r = -0.67)**.  

This indicates that the playlist is structurally organized around **production intensity** rather than genre labels. High-energy tracks tend to be louder and less acoustic, while more acoustic tracks cluster at lower energy levels.  

Despite genre diversity (rap, trap, R&B, pop, bachata), the playlist exhibits consistent audio-feature patterns centered on intensity and production style.
