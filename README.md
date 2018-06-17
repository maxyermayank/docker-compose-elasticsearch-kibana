# docker-compose-elasticsearch-kibana
Docker Compose for 3 Node Elasticsearch Cluster and Kibana Instance for development purposes

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

### Access Elasticsearch
```
http://localhost:9200
```