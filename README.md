# media_server

- [plex](https://github.com/plexinc/pms-docker)
- [bazarr](https://github.com/linuxserver/docker-bazarr)
- [calibre](https://github.com/linuxserver/docker-calibre)
- [calibre-web](https://github.com/linuxserver/docker-calibre-web)
- [heimdall](https://github.com/linuxserver/docker-heimdall)
- [qbittorrent](https://github.com/linuxserver/docker-qbittorrent)
- [radarr](https://github.com/linuxserver/docker-radarr)
- [sonarr](https://github.com/linuxserver/docker-sonarr)
- [unifi-controller](https://github.com/linuxserver/docker-unifi-controller)

Requirements
------------

- Docker: https://docs.docker.com/get-docker/

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
│   ├── bazarr
│   ├── calibre
│   ├── calibre-web
│   ├── heimdall
│   ├── plex
│   ├── qbittorrent
│   ├── radarr
│   ├── sonarr
│   └── unifi-controller
├── downloads
└── media
    ├── anime
    ├── books
    ├── movies
    ├── photos
    ├── shows
    └── transcode
```
