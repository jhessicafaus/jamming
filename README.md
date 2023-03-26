# Jamming

React app that allows users to create and save a playlist to Spotify.

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app) and used the [Spotify API](https://developer.spotify.com/).

## See it live

The project was deployed with [surge](https://surge.sh/).
See it live at [jamming_jamming.surge.sh](http://jamming_jamming.surge.sh/).

## Potential new features

* Pressing enter triggers a search
* Include preview samples for each track
* Only display songs not currently present in the playlist in the search results
* Add a loading screen while playlist is saving
* Update the access token logic to expire at exactly the right time, instead of setting expiration from when the user initiates their next search
* After user redirect on login, restoring the search term from before the redirect
* Ensure playlist information doesn’t get cleared if a user has to refresh their access token
* Provide a way to fetch and see all your existing playlists

## Run this project on your machine

Clone the repository.

In the project directory, you can run the app in the development mode:

### `npm start`

For the project to run in your browser:

* Open [http://localhost:3000](http://localhost:3000) to view it in your browser.
* To link your app with the spofity API, [access the spotify for developers dashboard](https://developer.spotify.com/dashboard/applications)
* Create an app, get the client ID. In the /util directory, inside the Spotify.js file, insert your own Spotify Client ID in the first line of code. (This project assumes you are familiarised with API key usage).
* Inside your project in the Spotify developer dashboard, go to edit settings. In "Redirect URIs", paste "http://localhost:3000" (or the address where your project is running). The address where you want your project to run and the address inside your app have to be exactly the same.


