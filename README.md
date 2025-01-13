# Netflix Data Analysis

## Overview
This project dives deep into Netflix's extensive catalog by analyzing a dataset containing detailed information about movies and TV shows. The analysis explores various dimensions, including content ratings, directors, actors, production trends over the years, and even sentiment analysis of content descriptions. This data-driven approach provides valuable insights into the world's leading streaming platform.

## Dataset
The dataset used for this analysis is netflix_titles.csv, which includes the following columns:

show_id: Unique identifier for each show.

type: Content type (Movie or TV Show).

title: Title of the content.

director: Director(s) associated with the content.

cast: Main cast of the content.

country: Country where the content was produced.

date_added: Date the content was added to Netflix.

release_year: Year of release.

rating: Content rating (e.g., PG-13, R).

duration: Duration of the content (applicable to movies).

listed_in: Genre(s) or categories of the content.

description: Brief synopsis of the content.

## Installation

To run the analysis, you need to have the following libraries installed:

```bash
pip install numpy pandas plotly textblob
