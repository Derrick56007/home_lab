# media_server

- [plex](https://github.com/plexinc/pms-docker)
- [deemix](https://gitlab.com/Bockiii/deemix-docker)
- [filerun](https://hub.docker.com/r/afian/filerun/)
- [jellyfin](https://hub.docker.com/r/linuxserver/jellyfin)
- [nginx-proxy-manager](https://hub.docker.com/r/jc21/nginx-proxy-manager)
- [portainer](https://hub.docker.com/r/portainer/portainer)

Requirements
------------

- Docker: https://docs.docker.com/get-docker/

(optional)

- Docker Compose: https://docs.docker.com/compose/install/

Usage
-----

```
docker-compose up -d
```

Update
------

```
docker-compose pull
```


Drive Structure
---------------
```
B_DRIVE/
├── configs
│   ├── portainer
│   ├── jellyfin
│   ├── nginx
│   ├── filerun
│   ├── plex
│   └── deemix
└── media
    ├── anime
    ├── books
    ├── movies
    ├── photos
    ├── shows
    └── transcode
```
