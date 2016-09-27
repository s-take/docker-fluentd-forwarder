# docker-fluentd-forwarder

## 事前準備

docker run で logging driver を fluentd に設定し、送信先を自分の docker network の GW に設定しておく。

## docker run

```
docker run -d  -e "td_server=xx.xx.xx.xx" stake/docker-fluentd-forwarder
```
