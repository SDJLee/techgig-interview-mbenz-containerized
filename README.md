# techgig-interview-mbenz-containerized

## Intro

This repo is to run the docker image of the repo [techgig-interview-mbenz](https://github.com/SDJLee/techgig-interview-mbenz) along with ELK stack, graphite, statsd and grafana using docker compose.

`MODE=prod SHIPLOGS=true GRAPHITE_URL=graphite:8125 LOGSTASH_URL=logstash:8089 docker-compose up`

The [docker-compose.yml](./docker-compose.yml) file uses prebuilt image of  [techgig-interview-mbenz](https://github.com/SDJLee/techgig-interview-mbenz) from docker hub.