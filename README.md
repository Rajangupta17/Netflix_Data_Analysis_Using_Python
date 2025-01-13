# Netflix Data Analysis

## Overview
This project involves analyzing Netflix's catalog using a dataset containing information about various movies and TV shows. The analysis covers various aspects such as content ratings, directors, actors, production trends over the years, and sentiment analysis of the content descriptions .

## Dataset
The dataset used for this analysis is `netflix_titles.csv`, which contains the following columns:
- `show_id`: Unique identifier for each show.
- `type`: Type of the content (Movie or TV Show).
- `title`: Title of the content.
- `director`: Director(s) of the content.
- `cast`: Main cast of the content.
- `country`: Country where the content was produced.
- `date_added`: Date the content was added to Netflix.
- `release_year`: Year the content was released.
- `rating`: Content rating.
- `duration`: Duration of the content (for movies).
- `listed_in`: Genre(s) the content belongs to.
- `description`: Brief description of the content.

## Installation

To run the analysis, you need to have the following libraries installed:

```bash
pip install numpy pandas plotly textblob
