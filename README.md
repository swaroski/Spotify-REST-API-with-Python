# Spotify-REST-API-with-Python
Based on simple REST principles, the Spotify Web API endpoints return JSON metadata about music artists, albums, and tracks, directly from the Spotify Data Catalogue.

![spotify](https://user-images.githubusercontent.com/25379742/106225408-11c38a80-61b3-11eb-8640-cd3688fb79c1.jpg)


Web API also provides access to user related data, like playlists and music that the user saves in the Your Music library. Such access is enabled through selective authorization, by the user.

The base address of Web API is https://api.spotify.com. The API provides a set of endpoints, each with its own unique path. To access private data through the Web API, such as user profiles and playlists, an application must get the user’s permission to access the data. Authorization is via the Spotify Accounts service.

Requests
The Spotify Web API is based on REST principles. Data resources are accessed via standard HTTPS requests in UTF-8 format to an API endpoint. Where possible, Web API uses appropriate HTTP verbs for each action:


