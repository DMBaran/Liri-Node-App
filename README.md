# Liri-Node-App

* Click on the (clone or download) button.

* Click on the clipboard to copy the url.

* Open your Terminal/Bash window and __*cd*__ (change directory) to your desktop.

* type __*git*__ clone and then paste the url.

* Cd into the repository (Liri-Node-App) you just cloned.

* Once you're in the repository you'll need to install 3 node packages.  
    * write __*npm install twitter*__ in your command line.
    * write __*npm install dotenv --save*__ in your command line.
    * write __*npm install --save node-spotify-api*__ in your command line.

* Create a __.env__ file in your reposity.

* Open your .env file and copy this into your file.

# Spotify API keys

SPOTIFY_ID=your-spotify-id

SPOTIFY_SECRET=your-spotify-secret

# Twitter API keys

TWITTER_CONSUMER_KEY=your-twitter-consumer-key

TWITTER_CONSUMER_SECRET=your-twitter-consumer-secret

TWITTER_ACCESS_TOKEN_KEY=your-access-token-key

TWITTER_ACCESS_TOKEN_SECRET=your-twitter-access-token-secret

* Replace the __(your-spotify-id)__ and __(your-spotify-secret)__ with your 
    spotify API keys.

* Replace the __(your-twitter-consumer-key)__, __(your-twitter-consumer-secret)__, 
    __(your-access-token-key)__ and __(your-twitter-access-token-secret)__ with your
    Twitter API keys.

* Once you've reached this point open your command line and cd into your Liri-Node-App.

* on your command line type __*node liri.js*__ and one of the following.
    * my-tweets __*@name*__ for your twitter.
    * movie-this __*any movie name*__.
    * spotify-this-song __*song name*__.