#run logstash with docker
```
sudo docker run --rm -it -p 5400:5044 -v `pwd`/settings:/config-dir docker.elastic.co/logstash/logstash-oss:6.2.4 -f /config-dir/logstash.conf
```
