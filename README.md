:notes: soundcloud streaming :notes: 
===========================


This data stream acquired using the [souncloud api](https://developers.soundcloud.com/docs/api/reference) polls soundcloud every 5 seconds to see if someone has created any new music on the platform. 

It is a representaion of the plethora of creativity channeled by people across the globe in to beautiful sonic landscapes

### Usage

1. clone and get up in that folder
2. `websocketd --port=8080 --staticdir=. python monitor-soundcloud.py`
3. open a new terminal tab and run: `python -m SimpleHTTPServer`
4. open Chrome and navigate to: `localhost:8000`
5. Bask in the beauty of the data stream.