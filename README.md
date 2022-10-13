# Full Pipeline (API to Viz) Spotify Data Project

## Goal is to create a 'full-stack' data project, where we build out a full solution allowing a user to explore their Spotify listening habits

## **Game Plan**

### Step One - Pulling the data
- Spotify provides an [API](https://developer.spotify.com/documentation/web-api/) that can be used to pull a variety of data for a user (or Spotify in general)
- For convenience (and skill/job relevancy), the API will be accessed via [spotipy](https://github.com/plamere/spotipy), a Python wrapper for the above linked API
- The API 'secrets' are manaaged through environment variables, and so if you wanted to clone and use this code for yourself, you will need to generate and store these with your own credentials (as demonstrated [here](https://www.youtube.com/watch?v=3RGm4jALukM))
- Following examples from spotipy's [documentation page](https://spotipy.readthedocs.io/en/master/) (and the Spotify **full** API documentation), we are able to pull 'current_user_recently_played' records to begin building our data



