# Spotify Genre Analysis: Popularity and Acousticness Trends
This repository contains an analysis of Spotify data in Tableau.
## Project Overview
Analysis of over 232,000 Spotify tracks examining genre distribution and acoustic characteristics to uncover patterns in music consumption and production styles.

## 📊 Visualizations

### Genre Popularity Distribution
![Genre Popularity Analysis](genre-popularity-chart.png)
### Genre Acousticness Analysis
![Genre Acousticness Analysis](genre-acousticness-chart.png)

## Key Findings
### Genre Popularity Insights
The analysis revealed significant differences in genre representation across Spotify's catalog:

- **Top 3 Most Popular Genres**: Pop (625,020 tracks), Rap (558,848 tracks), and Rock (543,043 tracks) dominate the platform, collectively representing a substantial portion of available music.
- **Least Popular Genres**: A Cappella, Children's Music, and Movie soundtracks have minimal representation, suggesting niche audience appeal or limited commercial production.

**Business Application**: Radio stations and streaming platforms could optimise listener engagement by prioritising Pop, Rap, and Rock during peak listening hours, as these genres have the broadest appeal based on catalog availability and likely reflect listener preferences.

### Acousticness Patterns by Genre
The acousticness metric (measuring reliance on acoustic vs. electronic instruments) revealed distinct production characteristics across genres:

- **Highly Acoustic Genres**: Opera (0.95), Classical (0.85), and A Cappella (0.80) rely almost entirely on acoustic instrumentation, reflecting traditional performance styles.
- **Electronic-Heavy Genres**: Electronic, Dance, and Ska show the lowest acousticness values, consistent with their reliance on synthesisers, drum machines, and digital production.
- **Surprising Finding**: Comedy recordings showed high acousticness (~0.75), highlighting that stand-up albums are essentially pure vocal performances without musical backing.

**Business Application**: Streaming platforms could leverage these insights to create targeted playlists. For example, a curated "Unplugged" or "Acoustic Sessions" playlist could feature Opera, Classical, and A Cappella tracks to serve listeners who prefer music without electronic amplification.

## Methodology

**Tools Used**
- **Tableau**: Data visualization and exploratory analysis
- **Excel**: Initial data handling and upload to Tableau
  
**Analysis Approach**:
1. Calculated total track counts by genre to identify popularity patterns
2. Computed average acousticness values by genre to understand production characteristics
3. Created horizontal bar charts for easy genre comparison and readability

**Variables Analysed**:
- Genre (categorical)
- Popularity (measured by track count)
- Acousticness (0-1 scale, where 1 = fully acoustic)


- # Potential Extensions

- Analyse temporal trends: How has genre popularity shifted over decades?
- Correlation analysis: Examine relationships between acousticness and other audio features (energy, danceability, valence)
- Market segmentation: Identify listener personas based on genre preferences and audio characteristics

*This project demonstrates skills in data visualization, pattern recognition, and translating analytical insights into actionable business recommendations.*
