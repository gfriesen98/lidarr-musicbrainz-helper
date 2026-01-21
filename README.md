# lidarr-musicbrainz-helper
A crappy html page to help add new artists to your Lidarr instance

## How to use
1. Download `index.html` from this repository. It doesnt matter if you clone the repo or just open `index.html` in the browser and copy paste it
2. Open `index.html` in your editor of choice
3. Scroll down to line 119 and 120
  - You need to edit `LIDARR_URL‎` and `LIDARR_API_KEY`
  - `LIDARR_URL` is the http/s address to your lidarr instance. It can be your ip address + port, wherever it is accessed in your browser
  - `LIDARR_API_KEY` is found in Lidarr Settings -> General -> Security
4. Now you can open `index.html` in your browser to search musicbrainz artists and add whatever is returned to Lidarr
