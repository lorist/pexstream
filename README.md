# pexstream
docker container for streaming using HLS

`git clone https://github.com/lorist/pexstream.git`
`cd pexstream`

`docker build -t pexstream .`

`docker run -p 80:80 -p 1935:1935 -d --name=ps pexstream`

Dial out from VMR:
rtmp://<dockerIP>:1935/live/<stream_name

View http://<dockerIP>
                                         
