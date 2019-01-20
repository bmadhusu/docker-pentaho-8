Run with something like this:

Current version 8.2

`docker build https://github.com/TornMarketing/docker-pentaho-8.git`

`docker run --restart=always --name=pentaho-server -itd -p 8080:8080 pentaho-server`

