# docker-compose-elasticsearch-kibana

## Overview
Docker Compose for 3 Node Elasticsearch (6.5.0) Cluster and Kibana (Open Source 6.5.0) Instance for development purposes.

Kibana is being served behind Nginx Proxy so you can secure access of kibana for your purpose.

## Requirements
1. Docker 18.05
2. Docker-compose 1.21

### Start Stack in Daemon Mode
```
docker-compose up -d
```

### Check status of docker-compose cluster
```
docker-compose ps -a
```

### Cluster Node Info
```
curl http://localhost:9200/_nodes?pretty=true
```

### Access Kibana
```
http://localhost:5601
```

### Accessing Kibana through Nginx
```
http://localhost:8080
```

### Access Elasticsearch
```
http://localhost:9200
```

# Resources
* [Hands on Elasticsearch](https://medium.com/@maxy_ermayank/hands-on-elasticsearch-8fa59d8aebfc)
* [Elasticsearch Resources](https://medium.com/@maxy_ermayank/elasticsearch-resources-27d24f01c1dc)
