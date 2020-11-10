<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Project3--Gnoosic-API-and-Web-Scraping
*[Sergio Monge]*

*[Data analytics, Barcelona October 2020]*

## Content
- [Project Description](#project-description)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)


## Project Description
The objective of this project is to recommend a song based on a user song input. If the song is hot at the moment, it recommends another hot song to listen to. If not, it looks up for that song through Spotify and suggest one with similar audio features as the one song chosen.


## Workflow
1. Web scraping of Billboard HOT 100 list.
2. Retrieve of playlists needed from Spotify API to populate the database.
3. Classify songs database in clusters in order to group songs with similar features together.
4. Set a function to get audios features from Spotify for each song input and recommend a similar one based on those features.



## Organization
- Playlist extractions: songs extracted from Spotify playlists to populate databas
- data : CSVs needed to work with different dataframes
- pickle: pickle files to store variables from a notebook to another
- Clustering extraction notebook
- Song recommender notebook

## Links

[Repository](https://github.com/segis23/Project3--Gnoosic-API-and-Web-Scraping)  
[Slides](https://docs.google.com/presentation/d/1PBQWmFM-ytWRXd7KKyfvhmGApEHsmJSEldTMHib1r_g/edit?usp=sharing)  
