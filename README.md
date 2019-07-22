# openjdk with jmx for docker running

 use jmxtrans  && jmx-expoter for expose promethues metrics

## how to running

* config jmxtrans config file

jmxtrans.json file, add some query for watch

* build image

```code
docker-compose build
```

* start

```code
docker-compose up -d
```

## view graphite && promethues metrics


* graphite

```code
open http://hostip
```

* promehtues metrics

```code
open http://hostip:9999
```