# PHP-Playground

A very simple dockerized PHP playground.

## Prerequisites
- Docker
- Docker-Compose

## Running it

To start it up, just run:
```
docker-compse up
```

The project directory will be served with the built-in PHP dev-server and bound to port 80 on your host.

You can open the browser pointing to `127.0.0.1` and fiddle around in the index.php, and/or create own files and point your browser to `127.0.0.1/<own-file-name>`.

For now, this playground does not contain a fully fledged web server such as nginx or Apache.