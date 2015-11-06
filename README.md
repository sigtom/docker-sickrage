# docker sickrage

This is a Dockerfile to set up "SickRage" - (https://sickrage.tv/forums/)

Build from docker file

```
git clone git@github.com:timhaak/docker-sickrage.git
cd docker-sickrage
docker build -t sickrage .
```

docker run --restart=always -d -h *your_host_name* -v /*your_config_location*:/config  -v /*your_videos_location*:/data -p 8081:8081 sickrage

[![Deploy to Tutum](https://s.tutum.co/deploy-to-tutum.svg)](https://dashboard.tutum.co/stack/deploy/)
