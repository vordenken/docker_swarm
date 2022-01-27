# My docker swarm setup

This is my collection of .yml files for docker. 

These containers are running on my raspberry Pi 4 (2GB Version), Raspberry Pi OS 64bit.

Docker is installed like usual and docker swarm is enabled: ```docker swarm init```

To use it yourself, clone the repository, cd inside it and run e.g. 

```docker stack deploy -c XXX.yml YYY```

Where *XXX.yml* is the file/container you want to run and *YYY* is the name docker assigns to it. For me XXX=YYY (I name the containers like the files)

