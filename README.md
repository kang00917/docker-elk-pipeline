# Elastic Stack Pipeline
- using Docker

### Quick start
```
docker-compose up
docker-compose -f docker-compose.yml up
docker-compose ls
docker ps
docker volume ls
```

### docker-compose file

#### docker-compose.yml
- Dockerfile를 가지고 ELK실행

#### docker-compose.simple.yml
- docker image만으로 elasticsearch, kibana를 실행

### Project List

- project01 : Logstash (HTTP input plugin) & codec JSON 
- project02 : Logstash (File input plugin & filter plugin) & apache log 파싱
- project03 : MetricBeat & 시스템 메트릭
- project04 : FileBeat & Logstash (Beats & Grok Plugin) & 로그파일수집
- project05 : Multi Node Elasticsearch Cluster
- project06 : Beats, Kafka, Logstash, Elasticsearch, Kibana
