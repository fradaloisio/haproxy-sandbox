# HAProxy sandbox

This repo contains the docker-compose file and the haproxy configuration to start a small sandbox to play with.

The HAProxy version is **2.2-alpine** if you are going to change the alpine version with the standard version, please keep in mind that the haproxy.cfg path could change.

As the application to be proxied the [lgirardi/pythbak](https://hub.docker.com/r/lgirardi/pytbak) image is used since it supports all the HTTP methods.
