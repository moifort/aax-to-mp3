# aax-to-mp3

1. Get your Amazon token looks `diid1093`
2. `docker run -it -v /your/aax/folder:/data moifort/aax-to-mp3 bash`
3. inside the docker `./AAXtoMP3 {YOUR_TOKEN} /data/yourAAX.aax`
