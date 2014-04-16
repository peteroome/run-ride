# run-ride
A print design by [@zoltarSpeaks]("http://twitter.com/zoltarSpeaks").

This print was built using my exercise data that i'd recorded on both Strava and RunKeeper.

## Tools
Javascript
D3.js
Html
Css

Starting it up…
$ cd /home/somedir
$ python -m SimpleHTTPServer

### Convert to geojson, exmaples
for f in myfolder/*; do TMXResolutionTool $f <otherparameters> ; done
for f in ~/Desktop/d3/data/gpx/*.gpx; do togeojson $f > $f.geojson ; done
for f in ~/Desktop/d3/data/gpx/*.gpx; do $f ; done 

### List of data files:
cd into/directory/containting/geojson/files
irb
Dir["2013*.geojson"]