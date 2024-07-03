# Netflix-movies-and-TV-shows-Dashboard
Power BI Dashboard

This repository contains the analysis of the Netflix Titles dataset, which includes details on movies and TV shows available on Netflix.

## Dataset Overview

The Netflix Titles dataset contains 8,809 entries, each representing a unique movie or TV show. The dataset includes the following columns:

- **show_id**: A unique identifier for each title.
- **type**: The category of the title, which is either 'Movie' or 'TV Show'.
- **title**: The name of the movie or TV show.
- **director**: The director(s) of the movie or TV show. (Contains null values for some entries, especially TV shows where this information might not be applicable.)
- **cast**: The list of main actors/actresses in the title. (Some entries might not have this information.)
- **country**: The country or countries where the movie or TV show was produced.
- **date_added**: The date the title was added to Netflix.
- **release_year**: The year the movie or TV show was originally released.
- **rating**: The age rating of the title.
- **duration**: The duration of the title, in minutes for movies and seasons for TV shows.
- **listed_in**: The genres the title falls under.
- **description**: A brief summary of the title.

## Power BI Dashboard

A comprehensive Power BI dashboard has been created to visualize the insights from the dataset. The dashboard includes:


- A Filled map to show the total movie and TV shows produced by different countries
- A Donut chart for the total number of category of the title
- A area chart to show the release year of the title
- A stacked bar chart for the ratings
- A stacked bar chart for the genres
- Added Card for showing 'Total titles', 'Total ratings', 'Total country', 'Total genres', 'Start year', 'Last year', 'Latest added date'

## Analysis Overview

### Content Analysis
- **Genre Popularity Over Time**: Analyze the trends in genre popularity over different years.
- **Distribution of Content Production Across Different Countries**: Determine which countries produce the most content and how this distribution has changed over time.
- **Trends in Movie vs. TV Show Production**: Compare the number of movies and TV shows released each year.

### Market Analysis
- **Netflix's Content Strategy**: Analyze patterns in `date_added`, `country`, and `listed_in` to understand Netflix's focus areas.
- **International Markets**: See how much content is produced in different countries and how much Netflix is investing in various regions.
- **Genre Diversification**: Assess the variety of genres Netflix is investing in.
- **Investment in Original Content**: Analyze the growth and distribution of Netflix originals.
