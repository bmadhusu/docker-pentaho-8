Run with something like this:

docker build https://github.com/TornMarketing/docker-pentaho-8.1.git

`docker run --restart=always --name=pentaho-server -itd -p 8080:8080 pentaho-server`

