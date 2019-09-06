# pexstream
docker container for streaming using HLS

`git clone 
`docker build -t pexstream .`

docker run -p 80:80 -p 1935:1935 -d --name=ps pexstream
rtmp://10.61.1.48:1935/live/dennis
